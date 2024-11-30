# **Hash Function**  

#### Translation by [ChatGPT](https://chatgpt.com/)

| References | Meanings | Thai Translation |
| ---- | ---- | ---- |
| [CISSP Glossary - Student Guide](https://www.isc2.org/certifications/cissp/cissp-student-glossary#h) | Accepts an input message of any length and generates, through a one-way operation, a fixed-length output called a message digest or hash. | รับข้อความอินพุตที่มีความยาวใด ๆ และสร้างผลลัพธ์ที่มีความยาวคงที่เรียกว่า message digest หรือ hash ผ่านการทำงานแบบทางเดียว |
| [NIST Glossary](https://csrc.nist.gov/glossary) | A function on bit strings in which the length of the output is fixed. Approved hash functions are designed to satisfy the following properties: (One-way) It is computationally infeasible to find any input that maps to any new pre-specified output, (Collision-resistant) It is computationally infeasible to find any two distinct inputs that map to the same output. | ฟังก์ชันที่ทำงานกับบิตสตริง ซึ่งความยาวของผลลัพธ์มีความคงที่ ฟังก์ชัน hash ที่ได้รับการอนุมัติได้รับการออกแบบให้ตอบสนองคุณสมบัติต่อไปนี้: (ทางเดียว)เป็นการคำนวณที่ไม่สามารถทำได้ในทางปฏิบัติในการหาข้อความอินพุตใด ๆ ที่แผ่ไปยังผลลัพธ์ที่กำหนดไว้ล่วงหน้า, (ต้านการชนกัน) เป็นการคำนวณที่ไม่สามารถทำได้ในทางปฏิบัติในการหาข้อความอินพุตสองชุดที่แตกต่างกันที่แผ่ไปยังผลลัพธ์เดียวกัน |

#### Translation by [Gemeni](https://gemini.google.com/)

| References | Meanings | Thai Translation |
| ---- | ---- | ---- |
| [CISSP Glossary - Student Guide](https://www.isc2.org/certifications/cissp/cissp-student-glossary#h) | Accepts an input message of any length and generates, through a one-way operation, a fixed-length output called a message digest or hash. | รับข้อความป้อนเข้าที่มีความยาวได้ไม่จำกัด และสร้างขึ้น ผ่านกระบวนการทางเดียว ผลลัพธ์ที่มีความยาวคงที่ เรียกว่า "ค่าแฮช" หรือ "ค่าดิกเจสต์ของข้อความ" |
| [NIST Glossary](https://csrc.nist.gov/glossary) | A function on bit strings in which the length of the output is fixed. Approved hash functions are designed to satisfy the following properties: (One-way) It is computationally infeasible to find any input that maps to any new pre-specified output, (Collision-resistant) It is computationally infeasible to find any two distinct inputs that map to the same output. | ฟังก์ชันที่ทำงานกับสตริงของบิต โดยมีความยาวของผลลัพธ์คงที่ ฟังก์ชันแฮชที่ได้รับการรับรองนั้นถูกออกแบบมาเพื่อให้ตรงตามคุณสมบัติต่อไปนี้ (One-way) เป็นไปไม่ได้ในทางปฏิบัติที่จะหาอินพุตใด ๆ ที่แมปไปยังเอาต์พุตที่กำหนดไว้ล่วงหน้า, (Collision-resistant) เป็นไปไม่ได้ในทางปฏิบัติที่จะหาอินพุตที่แตกต่างกันสองอินพุตใด ๆ ที่แมปไปยังเอาต์พุตเดียวกัน |

#### My Definition
> Hash Function คือ ฟังก์ชันทางคณิตศาสตร์ที่ใช้รับข้อมูลความยาวใดๆ และแปลงข้อมูลให้อยู่ในรูปแบบที่มนุษย์ไม่สามารถอ่านเข้าใจได้เช่น เลขฐาน 16 โดยมีความยาวเท่าเดิมกับข้อมูลเข้า เรียกว่า แฮช (Hash) โดยการ Hash แบ่งออกเป็น 2 ประเภทคือ 1. One-way คือการ Hash ที่ไม่สามารถย้อนกลับได้ 2. Collision-resistant คือการ Hash เพื่อลดโอกาสในการชนกันของข้อมูล

#### Everyday Scenario
> การเก็บรหัสผ่านบนฐานข้อมูลของเว็บไซต์ รหัสผ่านของผู้ใช้งานโดยส่วนใหญ่จะถูกแปลงเป็นค่าแฮชก่อนจัดเก็บเข้าฐานข้อมูลเพื่อป้องกันการรั่วไหลของข้อมูล หากเกิดการรั่วไหลแต่ไม่สามารถย้อนค่า Hash กลับได้ก็ไม่สามารถอ่านข้อมูลได้