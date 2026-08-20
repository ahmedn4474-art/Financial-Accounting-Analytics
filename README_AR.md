# التحليلات المحاسبية: فحص قيود دفتر الأستاذ والتنبؤ بالتدفقات النقدية والسيولة

**إعداد:** أحمد نور الدين محمد  
**المؤهل والتخصص:** طالب محاسبة (السنة الثالثة)، معهد القاهرة الجديدة العالي | متدرب سابق في تحليل البيانات بالبنك التجاري الدولي (CIB)  
**البريد الإلكتروني:** ahmedn4474@gmail.com | **المستودع:** [https://github.com/ahmedn4474-art/Financial-Accounting-Analytics](https://github.com/ahmedn4474-art/Financial-Accounting-Analytics)  
**المجال التخصصي:** Financial Accounting, Treasury Liquidity & Cash Flow Management  
**البيانات المستخدمة:** General Ledger Accounting Transactions Dataset (100,000 transaction records across accounts and fiscal periods)  

---

## 1. ملخص تنفيذي وصياغة المشكلة

يحتاج مسؤولو الإدارة المالية والخزانة إلى أدوات كمية دورية لضمان سلامة قيود دفتر الأستاذ العام والتنبؤ بالاحتياجات النقدية. يقدم هذا المشروع مسارا محاسبيا متكاملا يتضمن التنبؤ بالسلاسل الزمنية للتدفقات النقدية (Holt-Winters & ADF) وفحص تباين الحسابات لكشف القيود الاستثنائية.

---

## 2. هيكل المشروع والملفات

`	ext
|-- data/                    # مجلد البيانات
|-- Financial_Fraud_Notebook.ipynb   # دفتر Jupyter Notebook مكتمل المخرجات والرسومات
|-- requirements.txt         # متطلبات وحزم بايثون
|-- README.md                # التقرير الفني باللغة الإنجليزية
|-- README_AR.md             # التقرير الفني باللغة العربية
`

---

## 3. كيفية تشغيل المشروع محليا

1. **نسخ المستودع (Clone):**
   `ash
   git clone https://github.com/ahmedn4474-art/Financial-Accounting-Analytics.git
   cd Project4_Financial_Accounting
   `

2. **تثبيت الحزم المطلوبة:**
   `ash
   pip install -r requirements.txt
   `

3. **فتح دفتر العمل:**
   `ash
   jupyter notebook Financial_Fraud_Notebook.ipynb
   `

---

*إعداد: أحمد نور الدين محمد — تحليلات البيانات المالية والكمية.*
