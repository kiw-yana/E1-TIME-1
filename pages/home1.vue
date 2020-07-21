<template>
  <div class="box">
    <v-container>
    <br>
    <img src="../img/you.jpg" width="200" height="200" style="border-radius: 5px;" >
    <v-alert
      outlined
      color="purple"
    >
      <div class="title">ประวัติส่วนตัว</div>
      <div>
        <br>
        <p>ชื่อ: นายธนนท์  ยะนา ชื่อเล่น: คิว อายุ: 20 ปี</p>
        <p>วันเกิด: วันเสาร์ที่ 5 พฤษภาคม พ.ศ.2543</p>
        <p>อาศัยอยู่: บ้านส้มป่อย อ.จัตุรัส จ.ชัยภูมิ เลขที่บ้าน: 238/1</p>
        <p>กำลังศึกษาอยู่ที่: วิทยาลัยเทคนิคชัยภูมิ</p>

      </div>
    </v-alert>
   </v-container>
  </div>
</template>

<script>
export default {
    layout:'default1'
}
</script>