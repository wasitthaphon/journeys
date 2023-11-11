# My journeys

## Bus timetable

เว็บบับทึกตารางการเดินรถตามกะ และสามารถคิดคำนวณค่าใช้จ่ายได้ตามมาสเตอร์ที่ตั้งไว้

Website bus timetable maintenance and can calculate cost according to master was set.

### Development tools

เครื่องมือที่ใช้พัฒนา

- Angular v15 Web framework (Frontend)
- .NET 7 (Backend)
- PostgreSQL (Database)

### Features

For architecture features

- JWT Authentication
- Entity Framework for accesing data on backend, and use LinQ for data operation.

For website features

- Cost calculation on each onwer report.
- 2D table timetable between Route and Shift for assigning buses.

## Manular

เว็บบันทึกคู่มือ บทความ บันทึกข้อมูลใด ๆ คล้าย ๆ การเขียนกระทู้สำหรับใช้ภายในองค์กร

Website that has purpose to be the documentation for an organization.

### Development tools

เครื่องมือที่ใช้พัฒนา

Stage 1 - Current

- Angular v16 Web framework (Frontend)
- .NET 7 (Backend)
- MSSQL

Stage 2 - Plan

- Angular v17
- .NET 7
- MongoDB

### Features

For website features

- Search by mixes on keywords, title and content using Levenshtein Algorithm.
- Public and Private documentation supported.

## Monitoring api

ถึงแม้ว่าจะมี Grafana ไว้คอยดู Monitoring ได้อยู่แล้ว แต่การมอนิเตอร์ต้องการนำข้อมูลแค่บางส่วนไปแสดงบน Dashboard อีกที่หนึ่ง
โดยที่อยากได้เพียงแค่ข้อมูล และบาง Service ก็ไม่ได้ใช้ Grafana และ Prometheus ต้องสร้างขึ้นมาเพื่อตรวจ Flow งานว่ายังโอเคอยู่หรือไม่

เครื่องมือที่ใช้พัฒนา

- Grafana
- Prometheus
- .NET 7
- Angular
- MongoDB ใช้สำหรับการตั้งค่า Config ใช้กำหนดการตกแต่งให้กับค่า Metric หรือใช้สำหรับควบคุมว่าจะดูค่า Metric อะไรบ้าง
- SQL
