## แบบรายงานผลปฏิบัติการทดลอง 
## เรื่อง Transmission Line Filter Design
### Sec 11 Group Butterbeer

จัดทำโดย<br /><br />

นายธนวินท์ ตระกูลเชวงดิฐ รหัสนิสิต 6410502044 <br />
นายธีรภัทร ถิรพาณิชยฺกุล รหัสนิสิต 641052095 <br />
นายนวพล กอบสกุลกาญจน์ รหัสนิสิต  6410502117 <br />
นายนันทวัจน์ มงคลพิทักษ์สุข รหัสนิสิต 6410502125<br />


เสนอ ผศ.ดร.เด่นชัย วรเศวต<br /><br />

รายงานนี้เป็นส่วนหนึ่งของรายวิชา ปฏิบัติการสถาปัตยกรรมและอุปกรณ์สื่อสาร รหัสวิชา 01205381 ภาควิชาวิศวกรรมไฟฟ้า คณะวิศวกรรมศาสตร์ มหาวิทยาลัยเกษตรศาสตร์ ปีการศึกษา 2566


### การทดลอง
### เริ่มต้นออกแบบจากการทำในโปรแกรม Sonnet<br/>
![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/ef3d7773-b2cf-443a-9b4a-c3bcde78772a)<br/>

### นำค่าที่ได้จากการทำในโปรแกรม Sonnet มาวาดกราฟใน Excel ได้กราฟตามรูปด้านล่างนี้<br/>
![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/7062a663-5bef-4d41-92e1-372034e6b7c3)<br/>

![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/f0e63c85-1953-4fec-8e6c-3563d698f8e7)<br/>

![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/d3184551-0d39-49f4-95a0-25f785c0a119)<br/>

![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/8f108024-e789-478e-b2e7-90cba2e2eb64)<br/>

### หลังจากนั้นนำไปทำของจริง โดยการนำไปทำในโปรแกรม Easy Eda <br/>
![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/5513d013-1612-4dfa-aeab-fe51469d7525)<br/>

### ผลลัพธ์จากการนำมาทดสอบ โดยนำค่าที่ได้จากเครื่องวัด มาวาดใน Excel<br/>
![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/acf34da7-98c1-4088-8038-df8e8d674c19)
![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/dc999e59-9da8-4c46-9d2e-8f7a71be5331)
![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/c9bb8d49-0c85-41f6-b749-c03a159ab15f)
![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/974a6be8-c537-4982-b5bb-5957c93e0950)<br/>

## กราฟที่ได้
![image](https://github.com/githubdcw/01205381-2023-2/assets/164730078/92602c0d-d676-4e41-8c5e-c9dd7a17985b)

## สรุปผลการทดลอง

จากการทดลองทำ Filter Design โดยเริ่มทำการออกแบบในโปรแกรม Sonnet ก่อน หลังจากนั้นนำมา ออกแบบต่อในโปรแกรม Easy EDA เพื่อสั่งทำของจริงขึ้นมา โดยจากการทดลอง ค่าที่ได้จากการจำลองในโปรแกรม มีค่าใกล้เคียงกับของจริงที่ออกแบบมา โดยอาจจะมีค่าคาดเคลื่อนอยู่บ้างในบ้างส่วน จากการออกแบบที่คาดเคลื่อน หรือที่ที่ขาบัดกรี กินเข้ามาในเนื้อทองแดงของตัว L ทำให้ค่าเปลี่ยนไป สรุปแล้วเมื่อสั่งเกตุจากกราฟทั้งสองแบบ จากการจำลองในโปรแกรม และของจริง จะทราบว่า Filter ตัวนี้มีการ Cut off -3 db ที่ 2.1 GHz จากการจำลอง และ 2.08 GHz จากของจริง ดังนั้นแล้ว Filter ตัวนี้สามารถใช้งานได้จริงตามการออกแบบ