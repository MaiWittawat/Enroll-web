<template>
    <div class="ml-10 mt-5 flex flex-col gap-3">
        <div class="text-[22px] font-bold">
            ยินดีต้อนรับเข้าสู่ระบบลงทะเบียนนิสิต
        </div>
        <div class="flex items-center text-[16px] gap-4 text-green-600">วันศุกร์ที่ 1 ธันวาคม
            <span class="text-[13.5px] bg-[#03A96B] px-3 py-0.5 text-white rounded-xl">ภาคปลาย 2566</span>
        </div>
    </div>

    <div
        class="items-center flex flex-col p-5 mt-4 justify-center w-full bg-gradient-to-r from-[#66C3D6] via-[#83D0E3] to-[#B1E3F5]">
        <h4 class="text-[20px]">นิสิตสามารถลงทะเบียนเรียนได้ตามวันเวลาดังนี้</h4>
        <br>
        <div class="gap-2 flex flex-col">
            <span>วันพฤหัสบดี, 23 พฤศจิกายน 2023เวลา 10:00 - 12:00 น.</span>
            <span>วันพฤหัสบดี, 23 พฤศจิกายน 2023เวลา 13:00 - 16:00 น.</span>
            <span>วันพฤหัสบดี, 23 พฤศจิกายน 2023เวลา 18:00 - 24:00 น.</span>
        </div>
    </div>

    <div class="mt-10 flex items-center justify-center">
        <div class="w-4/5">
            <div class="flex gap-4">
                <button class="px-4 py-2 border-2 rounded bg-[#28C3D7] text-white">รายวิชา</button>
                <button class="px-4 py-2 border rounded">ทั่วไป</button>
            </div>

            <div class="mt-5 border rounded shadow">
                <div class="border-b text-[20px] px-5 py-3 flex items-center gap-4">
                    <Icon name="majesticons:messages" size="40"
                        class="rounded-full p-2 bg-gradient-to-t from-pink-500 via-red-500 to-yellow-500" color="white" />
                    ประกาศรายวิชา
                </div>

                <div class="flex flex-col p-2 gap-4 text-gray-700">
                    <div class="border bg-green-50 p-4 rounded flex gap-4 flex-col">
                        <h3 class="font-bold">01418351-60 หลักการการสื่อสารคอมพิวเตอร์และการประมวลผลบนคลาวด์</h3>
                        <sec class="font-semibold flex items-center gap-2 text-[14px]">หมู่เรียน <span class="text-green-600">200</span>
                            <span class="px-2 bg-[#73BEDB] rounded-full text-white text-[12.5px] font-normal">บรรยาย</span></sec>
                        <span>LMS</span>

                        <div class="flex flex-col">
                            <date class="flex items-center gap-2"><Icon name="fluent-mdl2:clock" size="20"/>ล่าสุดเมื่อวันพุธ, 22 พฤศจิกายน 2566</date>
                            <by class="font-bold mt-0.5">โดย นางสุขุมาล กิติสิน</by>
                        </div>
                    </div>  


                    <div class="border bg-green-50 p-4 rounded flex gap-4 flex-col">
                        <h3 class="font-bold">01418351-60 หลักการการสื่อสารคอมพิวเตอร์และการประมวลผลบนคลาวด์</h3>
                        <sec class="font-semibold flex items-center gap-2 text-[14px]">หมู่เรียน <span class="text-green-600">200</span>
                            <span class="px-2 bg-[#73BEDB] rounded-full text-white text-[12.5px] font-normal">บรรยาย</span></sec>
                        <span>LMS</span>

                        <div class="flex flex-col">
                            <date class="flex items-center gap-2"><Icon name="fluent-mdl2:clock" size="20"/>ล่าสุดเมื่อวันพุธ, 22 พฤศจิกายน 2566</date>
                            <by class="font-bold mt-0.5">โดย นางสุขุมาล กิติสิน</by>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<script setup>

import axios from 'axios';
const data = reactive({})

const load = async () => {
    try {
        const res = await axios.get("https://jsonplaceholder.typicode.com/todos/1");
        if (res.status === 200) {
            // console.log(res.data)
            data.user = res.data
            console.log(data.user)
        }
    }
    catch (error) {
        console.log(error)
    }

}

load()

</script>
