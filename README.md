# Playwright Test Automation Final Exam

โครงการนี้เป็นส่วนหนึ่งของข้อสอบปฏิบัติ Playwright Automation Testing โดยทำการทดสอบระบบ Web Application (SauceDemo) ครอบคลุมทั้ง Unit/UI Component Testing และ Integration Testing

ข้อมูลผู้จัดทำ

- **ชื่อ-นามสกุล: นายกฤตยะ ไชยเทพ
- **รหัสนักศึกษา: 6804101303
- **สาขา/คณะ: สาขาวิชาวิทยาการคอมพิวเตอร์ คณะวิทยาศาสตร์ มหาวิทยาลัยแม่โจ้

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)

```text
.
├── .github/workflows/       # GitHub Actions สำหรับทำ CI/CD
├── reports/                 # โฟลเดอร์เก็บรายงานผลการทดสอบ
│   ├── html-report/         # Playwright HTML Report
│   └── test-summary.md      # สรุปผลการทดสอบ (Test Summary)
├── tests/                   # ชุดไฟล์ Test Scripts (รวม 6 ข้อ)
│   ├── unit/                # UT-01 ถึง UT-04 (UI Component Testing)
│   └── integration/         # IT-01 (Stub) และ IT-02 (Driver)
├── package.json             # รายการ Dependencies และ Scripts
├── playwright.config.ts     # การตั้งค่าหลักของ Playwright
└── README.md                # เอกสารอธิบายโปรเจกต์
