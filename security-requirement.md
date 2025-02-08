# **🔒 Security Requirement**  

## 8.2.1 Client-side Data Protection

#### Detail
> Verify the application sets sufficient anti-caching headers so that sensitive data is not cached in modern browsers.

#### ChatGPT
> การป้องกันไม่ให้ข้อมูลที่สำคัญถูกเก็บ (cached) บนเบราว์เซอร์ของผู้ใช้งาน ซึ่งอาจทำให้ข้อมูลเหล่านั้นถูกเข้าถึงได้โดยไม่ได้รับอนุญาตในภายหลัง

#### Gemini
> การตรวจสอบให้แน่ใจว่าแอปพลิเคชันของคุณได้กำหนดค่า HTTP headers ที่เหมาะสม เพื่อป้องกันไม่ให้ข้อมูลสำคัญถูกเก็บไว้ในแคชของเว็บเบราว์เซอร์

#### My Definition
> การป้องกันไม่ให้ ข้อมูลสำคัญ (เช่น รหัสผ่าน, Token, ข้อมูลส่วนตัว) ถูกเก็บไว้ใน ความจำชั่วคราวของเบราว์เซอร์ (Cache) เพราะถ้าเบราว์เซอร์เก็บข้อมูลเหล่านี้ไว้ คนอื่นที่ใช้เครื่องเดียวกันอาจแอบดูได้

#### Partner
- [Natchanan Lordee](https://ncnld2547.github.io/security-requirement)
