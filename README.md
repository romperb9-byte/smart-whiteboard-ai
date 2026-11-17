# ក្ដាខៀនឆ្លាតវៃ AI (Smart Whiteboard AI)

កម្មវិធីក្ដាខៀនឌីជីថលឆ្លាតវៃសម្រាប់គ្រូបង្រៀន សិស្ស និងការសិក្សាស្រាវជ្រាវ គាំទ្រការសរសេរដៃ គណនាលេខស្វ័យប្រវត្តិ (AI Handwritten Math Solver), គូសក្រាបអនុគមន៍ Oxy, អ័ក្ស 3D Oxyz និងគំរូរូបធរណីមាត្រ 3D (Three.js) ដោយផ្ទាល់នៅលើ Web Browser។

---

## 🌟 មុខងារសំខាន់ៗ (Features)
- 🔑 **វាលដាក់ Free Gemini API Key**៖ អាចបញ្ចូល API Key ឥតគិតថ្លៃដោយផ្ទាល់ពី Google AI Studio រក្សាទុកក្នុង browser (localStorage) មានសុវត្ថិភាពខ្ពស់។
- ✍️ **AI ស្គាល់ការសរសេរដៃ & គណនា (=)**៖ សរសេរប្រមាណវិធី ឬសមីការបញ្ចប់ដោយសញ្ញាស្មើ (`=`) AI នឹងដោះស្រាយ និងសរសេរចម្លើយនៅលើក្ដាខៀនដោយស្វ័យប្រវត្តិ។
- 📐 **Auto-Shape Recognition**៖ គូសរាងធរណីមាត្រដោយដៃ (បន្ទាត់, រង្វង់, ចតុកោណ, ត្រីកោណ) នឹងកែតម្រូវជារាងស្អាតស្វ័យប្រវត្តិ។
- 📈 **គូសក្រាបអនុគមន៍ & អ័ក្សកូអរដោនេ**៖ គូសក្រាប $y = f(x)$, តម្រុយអ័ក្ស 2D (Oxy) និងអ័ក្ស 3D (Oxyz) ដែលអាចចុចអូសបង្វិល 360° បាន។
- 🧊 **ស្ទូឌីយោគំរូ 3D (Three.js)**៖ បំប្លែងរូបគំនូរ ឬជ្រើសរើសរូបធរណីមាត្រ (Cube, Sphere, Cylinder, Cone, Pyramid, Revolve) បង្វិល 360° និងបញ្ចូលទៅលើក្ដាខៀនដោយគ្មានស៊ុម។
- 🏫 **ឧបករណ៍បង្រៀនស្ដង់ដារ**៖ បន្ទាត់វាស់ (cm), វាំងននបិទបាំងចម្លើយ (Screen Shade), ពិលបញ្ចាំង (Spotlight), និងម៉ាស៊ីនចាប់ឈ្មោះសិស្សដោយចៃដន្យ។
- 📄 **Multi-page Slides**៖ បង្កើតស្លាយទំព័រមេរៀនច្រើនទំព័រ, Undo/Redo, អានលទ្ធផលជាសំឡេង (Speech Synthesis)។

---

## 🔑 របៀបយក Google Gemini API Key ដោយឥតគិតថ្លៃ (Free 100%)
1. ចូលទៅកាន់គេហទំព័រ [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Sign in ជាមួយគណនី Google (Gmail) របស់អ្នក
3. ចុចលើប៊ូតុង **"Create API key"**
4. Copy API Key នោះ
5. បើកកម្មវិធីក្ដាខៀននេះ ចុចលើប៊ូតុង **"API Key"** នៅរបារខាងលើស្ដាំ រួច Paste និងចុច **"រក្សាទុក (Save)"** ជាការស្រេច!

---

## 🚀 របៀបដាក់ឱ្យដំណើរការនៅលើ GitHub (GitHub Pages Deployment)

### ជំហានទី ១៖ បង្កើត Repository ថ្មីនៅលើ GitHub
1. ចូលទៅកាន់ [GitHub.com](https://github.com) រួចចុច **New repository**
2. ដាក់ឈ្មោះ Repository ឧទាហរណ៍៖ `smart-whiteboard-ai`
3. ជ្រើសរើស **Public**
4. ចុច **Create repository**

### ជំហានទី ២៖ Push កូដឡើងទៅ GitHub
បើក Terminal / PowerShell នៅត្រង់ Folder គម្រោងនេះ រួចវាយពាក្យបញ្ជាខាងក្រោម៖

```bash
git init
git add .
git commit -m "Initial commit of Smart Whiteboard AI"
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/smart-whiteboard-ai.git
git push -u origin main
```
*(ចំណាំ៖ សូមប្ដូរ `<YOUR-USERNAME>` ទៅជាឈ្មោះគណនី GitHub របស់អ្នក)*

### ជំហានទី ៣៖ បើកដំណើរការ GitHub Pages
1. នៅក្នុង Repository របស់អ្នកនៅលើ GitHub ចុចលើ Tab **Settings**
2. នៅ Menu ខាងឆ្វេង រំកិលចុះក្រោម រួចចុចលើ **Pages**
3. នៅក្រោមចំណងជើង **Build and deployment**:
   - ចំណុច **Source**: ជ្រើសរើស `Deploy from a branch`
   - ចំណុច **Branch**: ជ្រើសរើស `main` និង `/ (root)`
4. ចុច **Save**
5. រង់ចាំប្រហែល 1 ទៅ 2 នាទី GitHub នឹងផ្ដល់ Link ដំណើរការផ្ទាល់ ឧទាហរណ៍៖
   `https://<YOUR-USERNAME>.github.io/smart-whiteboard-ai/`

---

## 💻 ដំណើរការនៅលើម៉ាស៊ីនផ្ទាល់ (Local Run)
គ្រាន់តែ Double-click បើកឯកសារ `index.html` នៅលើ Web Browser ណាមួយ (Chrome, Edge, Firefox, Safari) ជាការស្រេច ដោយមិនបាច់ដំឡើង Server ស្មុគស្មាញឡើយ!
