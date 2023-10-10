# COM-LAB-I-LabSheet-Week-14
## Git submodule และการใช้งาน git บน Visual studio

![Alt text](./Pictures/Picture-01.png)

## git submodule

git submodule นิยมใช้เพื่อรวม project ใน version อื่นๆ เข้ากับ project ที่มีอยู่ มีประโยชน์เมื่อแยกกันพัฒนาในลักษณะของ third party library หรือ Component Base Software Engineering 

git submodule ช่วยให้เราทันต่อการเปลี่ยนแปลงของ  component ภายนอก ซึ่งอาจจะพัฒนาโดยบุคคลอื่นอยู่เสมอ 

ในใบงานนี้เราจะได้เรียนรู้การ เพิ่ม แก้ไข ลบ submodule โดยมีตัวอย่างการพัฒนาเป็น application บน desktop ที่สามารถเพิ่มขยายขีดความสามารถด้วย component ที่เรียกว่า   plugins


![Alt text](./Pictures/Picture-03.png) 


## URL of source code

### Main program and Plugin Interface

https://github.com/6808-plugin-dev/PluginPrototype

### Plugin 1
https://github.com/6808-plugin-dev/plugin1

### Plugin 2
https://github.com/6808-plugin-dev/plugin2

### Plugin 3
https://github.com/6808-plugin-dev/plugin3

## ขั้นตอนการทำงาน

1. Fork/clone Main program and plugin interface repository

2. Add submodule for plugins

3. Configure location of plugins

4. Build – Test Application 


![Alt text](./Pictures/Picture-06.png)

![Alt text](./Pictures/Picture-07.png)

![Alt text](./Pictures/Picture-08.png)

![Alt text](./Pictures/Picture-09.png)

![Alt text](./Pictures/Picture-10.png)

![Alt text](./Pictures/Picture-11.png)

![Alt text](./Pictures/Picture-12.png)

![Alt text](./Pictures/Picture-13.png)

## การเพิ่ม plugins เป็น submodule

![Alt text](./Pictures/Picture-15.png)

![Alt text](./Pictures/Picture-16.png)

![Alt text](./Pictures/Picture-17.png)

![Alt text](./Pictures/Picture-18.png)




## การ clone repository มาเป็น submodule


- ใน git bash terminal ให้สร้าง branch ใหม่สำหรับทำงานกับ plugins 

   -  เราจะไม่ publish จนกว่าจะพัฒนา  plugin เสร็จ 

   -  สามารถเลือก plugin ที่จะมา merge กับ host ได้ในภายหลัง

- ใน git bash terminal ให้สร้าง folder  ใหม่สำหรับ plugins ทั้งหลาย

- Clone plugin1 มาเป็น submodule



![Alt text](./Pictures/Picture-20.png)

![Alt text](./Pictures/Picture-21.png)

![Alt text](./Pictures/Picture-22.png)

![Alt text](./Pictures/Picture-23.png)

![Alt text](./Pictures/Picture-24.png)

![Alt text](./Pictures/Picture-25.png)

![Alt text](./Pictures/Picture-26.png)

![Alt text](./Pictures/Picture-27.png)


## เพิ่ม submodule อื่น ๆ เข้ามาใน solution

ใน organization  https://github.com/6808-plugin-dev
จะมี plugins อีก 3-4 ตัว 

- ให้ทำการเพิ่มเป็น submodule ครั้งละตัว
   - ทำตามขั้นตอนที่ได้เรียนมา
   - การเพิ่มแต่ละตัวให้บันทึกหน้าจอที่ได้
- ถ้ามี error ใดๆ ให้บันทึกข้อความไว้ด้วย ให้สร้างเป็น issue ใน upstream repository

## การทำงานกับ submodule


![Alt text](./Pictures/Picture-30.png)

![Alt text](./Pictures/Picture-31.png)

![Alt text](./Pictures/Picture-32.png)

