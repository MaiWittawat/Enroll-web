<template>
    <div class="ml-10 mt-5 flex flex-col gap-3">
        <div class="text-[22px] font-bold">
            ตารางเรียน/ตารางสอบ
        </div>
        <div class="flex items-center text-[16px] gap-4 text-green-600">วันศุกร์ที่ 1 ธันวาคม
            <span class="text-[13.5px] bg-[#03A96B] px-3 py-0.5 text-white rounded-xl">ภาคปลาย 2566</span>
        </div>
    </div>

    <br>
    <hr>

    <div class="mt-10 flex items-center justify-center">
        <div class="w-[95%]">
            <div class="flex justify-between items-center">
                <div class="flex gap-0.5 text-[12.5px]">
                    <button class="px-6 py-1.5 rounded-l bg-[#03A96B] text-white">ตารางเรียน</button>
                    <button class="px-3 py-1.5 bg-[#DCDCDC] text-white">สอบกลางภาค</button>
                    <button class="px-3 py-1.5 rounded-r bg-[#DCDCDC] text-white">สอบปลายภาค</button>
                </div>


                <div class="bg-white border px-4 py-1 flex items-center justify-center">
                    27/11/2566 - 17/03/2567
                </div>


                <div class="flex border-r items-center px-4 text-[12.5px] h-[20px] gap-1">
                    <span>ทั้งหมด</span> <span class="text-blue-400"> 7 </span> <span>วิชา</span>
                </div>

            </div>

            <hr class="mt-4">

            <div class="mt-5 rounded">
                <div class="grid grid-cols-5 text-xs shadow">
                    <date class="bg-[#F7CD53] rounded h-[110px] flex justify-center flex-col gap-3 px-2 py-1 font-semibold">
                        <day>MON</day>
                        <time class="text-xl">12:30 - 15:30</time>
                        <Icon name="material-symbols:mark-unread-chat-alt-outline-sharp" size="20" />
                    </date>


                    <section class="flex p-4 text-xs font-semibold justify-center gap-2">
                        <span class="font-bold">01418362-65</span>
                        <span>หมู่ <span class="text-green-600 text-[13px] font-bold">200</span></span>

                        <div>
                            <span
                                class="px-2 mx-1 pb-0.5 text-[12px] bg-[#73BEDB] rounded-xl font-normal text-white">บรรยาย</span>
                        </div>
                    </section>


                    <content class="pl-2 col-span-2 flex flex-col py-4 gap-3">
                        <div>
                            <th-title class="font-bold">หลักการการสื่อสารคอมพิวเตอร์และการประมวลผลบนคลาวด์</th-title>
                            <eg-title class="font-medium">Computer Communications and Cloud Computing Principles</eg-title>
                        </div>

                        <teacher class="flex gap-1">
                            <div class="font-bold">อ.ผู้สอน</div> สุขุมาล กิติสิน
                        </teacher>
                    </content>

                    <room class="py-4">
                        <div><span class="font-bold">ห้อง</span> SC45-704</div>
                        <div><span class="font-bold">ประเภทหมู่เรียน</span> : พิเศษ</div>
                    </room>
                </div>


            </div>
        </div>
    </div>
</template>

<script setup>

</script>
