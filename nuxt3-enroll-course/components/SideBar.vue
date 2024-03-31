<template>
    <div class="grid w-full  min-h-screen">

        <div class="border-r border-gray-600 z-10 bg-[#282C34] text-gray-400">

            <div class="border-b-2 border-gray-700 h-[75px] flex gap-2 items-center justify-around">
                <div class="flex gap-2">
                    <img src="https://images.unsplash.com/photo-1569173112611-52a7cd38bea9?q=80&w=1887&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                        alt="profile" class="outline rounded-full object-cover outline-1 h-10 w-10">
                    <div class="leading-4">
                        <h3 class="font-bold text-green-500">วิทวัส พิณรัตน์</h3>
                        <span class="font-semibold text-[13px] text-gray-400">นิสิตปัจจุบัน</span>
                    </div>
                </div>

                <Icon name="fluent-mdl2:numbered-list-text" size="25" color="white" />
            </div>



            <ul class="font-semibold text-[15px] py-8">
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="material-symbols-light:mark-unread-chat-alt" size="20" /> ข่าวสารนิสิต
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="material-symbols:calendar-month" size="20" /> ตารางเรียน/ตารางสอบ
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="" size="20" /> วิชาที่เปิดให้ลงทะเบียน
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="material-symbols:attach-money" size="20" /> ชำระเงิน
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="" size="20" /> ลงทะเบียนเพิ่ม/ถอน
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="" size="20" /> ผลการลงทะเบียน
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="ri:graduation-cap-fill" size="20" /> ตรวจสอบผลการเรียน
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="" size="20" /> ประวิติการลงทะเบียน
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="" size="20" /> สถิติ
                </li>
                <li class="flex hover:bg-green-700 hover:text-white py-2 px-4 items-center ">
                    <Icon name="ri:account-box-fill" size="20" /> ประวัตินิสิต
                </li>
            </ul>

        </div>


    </div>
</template>

<script setup>

</script>
