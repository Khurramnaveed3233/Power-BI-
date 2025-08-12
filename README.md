#  Data Visualization Best Practices

Data visualization ka matlab sirf graph banake colors change karna nahi hai — ab visuals banane se pehle planning aur audience ko samajhna bohot zaroori hai.  
Neeche kuch simple best practices hain jo aapke visuals ko **clear, effective aur trustable** banayenge.

---

## 1️⃣ Apne Audience Ko Samjho
Visual banate waqt socho **kaun dekh raha hai**.  
Agar audience senior leaders ya executives hain, unke paas sirf kuch seconds hote hain — is liye **simple aur point-to-point visuals** banao.

**Example:**  
- **Marketing team** ke liye sales dashboard: product-wise sales trends + customer demographics.  
- **CEO** ke liye dashboard: monthly revenue, profit margin aur growth ka short summary.

 **Lesson:** Har audience ke liye visuals ko **customize** karo.

---

## 2️⃣ Context Do
Data ka background samjhana bohot important hai. Sirf "sales down" likhne se kaam nahi chalega — reason aur trend bhi dikhao.

**Example:**  
July me sales gir gayi? Chart ke sath pichle 6 mahine ka trend dikhao aur explain karo ke "Eid ke baad demand naturally kam hoti hai."

 **Lesson:** Context se audience samajh paati hai **kyun** fall ya rise hua.

---

## 3️⃣ Bias Na Rakho
Apne agenda ke liye data ko twist mat karo. Jo sach hai wahi dikhayo — chahe wo aapke favor me ho ya nahi.

**Example:**  
Project ka positive result dikhana chahte ho, lekin kuch regions me sales gir rahi hai. Agar yeh hide karoge to future decisions galat ho sakte hain.

 **Lesson:** Data **jaisa hai**, waisa hi dikhana trust banata hai.

---

## 4️⃣ Design Se Pehle Plan Banao
Bina plan ke visuals banana time waste ho sakta hai. Pehle decide karo:
- Kaunsa KPI dikhana hai?
- Kaunsa chart best hoga?
- Kaunsa filter apply hoga?

**Example:**  
SQL se data nikal ke direct Power BI me chart banane lage, baad me pata chala join galat tha. Time waste!  
Better: pehle paper pe design ka roadmap banao.

 **Lesson:** Pehle socho, phir design banao.

---

## 5️⃣ Data Accurate Rakho
Agar data sahi nahi hoga to visuals pe trust khatam ho jayega. Hamesha **latest, clean aur verified** data use karo.

**Example:**  
Excel file outdated thi, dashboard galat numbers dikhane laga, audience ka trust chala gaya.

 **Lesson:** Source verify karo aur data update rakho.

---

## 6️⃣ Test Run Karo
Final launch se pehle visuals ek chhote group ko dikhao, feedback lo, aur phir improve karo.

**Example:**  
Dashboard directly company me share kar diya, HR team ko metrics samajh nahi aaye.  
Better hota pehle test group se feedback lete.

 **Lesson:** Test → Feedback → Improve → Final Launch.

---

##  Recap
-  Audience ko samjho  
-  Context do  
-  Bias na rakho  
-  Pehle plan karo  
-  Data sahi ho  
-  Test run karo  

# Power BI Visuals – Purpose, Real-World Examples & When to Use

## 1. **Bar Chart / Column Chart**

<img width="486" height="166" alt="y0gaux3g-Screenshot1-Bar-and-Column" src="https://github.com/user-attachments/assets/3adeeac8-e1dc-4723-aef4-2572249e5af1" />

- **Purpose:**  
  Categories ke beech comparison dikhane ke liye.
  
- **Real-World Example:**  
  Sales by product category, number of students per department.
  
- **When to Use:**  
  Jab aapko discrete categories ka comparison chahiye, e.g., "Which product sold most?"

---

## 2. **Line Chart**

<img width="593" height="348" alt="line" src="https://github.com/user-attachments/assets/9cf58258-2ad2-4019-9cac-68c47091f3c3" />

- **Purpose:**  
  Time ke saath trend dikhane ke liye.
  
- **Real-World Example:**  
  Monthly revenue growth, website traffic over weeks.
  
- **When to Use:**  
  Jab aapko data ka trend dekhna ho, jaise increasing ya decreasing pattern.

---

## 3. **Pie Chart / Donut Chart**

<img width="486" height="166" alt="y0gaux3g-Screenshot1-Bar-and-Column" src="https://github.com/user-attachments/assets/e9693e99-64fa-41f3-ad5e-573bb0c62110" />

- **Purpose:**  
  Total ka percentage share dikhana.
  
- **Real-World Example:**  
  Market share by company, budget allocation percentage.
  
- **When to Use:**  
  Jab categories limited ho (3–6) aur proportion highlight karna ho.**

**Pie Chart kab use karna chahiye Power BI mein?**

<img width="520" height="332" alt="pie" src="https://github.com/user-attachments/assets/b84da919-fb32-43a7-a2ac-2a79a1a7ae9d" />

Pie chart tab use karna chahiye jab aapko apne data ke mukhtalif hisson ka total ke muqablay mein hisa dikhana ho. Yeh chart percentages ya proportions ko visualize karne ke liye best hota hai.

Misal ke taur par, agar aap sales data mein alag-alag products ki sales ka hisa dekhna chahte hain, to pie chart use karke har product ka sales total mein kitna percent hai, asani se samajh sakte hain.

**Donut Chart kab use karna chahiye Power BI mein?**

![donut-chart-main-1](https://github.com/user-attachments/assets/b4f8c4ba-5b97-4009-8fd2-8c684e7d8d7d)

Donut chart pie chart ki tarah hota hai, lekin ismein center khali hota hai jo thoda modern aur clean nazar aata hai. Donut chart tab use karna chahiye jab aapko apne data ke parts ka total mein hissa dikhana ho, magar aap thoda zyada visual appeal aur behtareen labeling chahte hon.

Misal ke taur par, agar aapko apni company ke department-wise kharch ka breakdown dikhana ho, to donut chart se aap asani se har department ke kharch ka hisa total budget mein samajh sakte hain.

## 4. **Area Chart**

<img width="635" height="468" alt="power-bi-chart-example" src="https://github.com/user-attachments/assets/42e40a6b-de19-460b-aad9-f30a03f7b6d9" />

**Basic Area Chart** 

(jise layered area chart bhi kehte hain) line chart par mabni hota hai. Axis aur line ke darmiyan jo area hota hai usay rangon se bhar diya jata hai taake volume ka izhar ho.

Area charts waqt ke sath tabdeeli ki magnitude par zor dete hain, aur kisi trend ke total value par tawajjo dene ke liye istemal hotay hain. Misal ke taur par, woh data jo profit ko waqt ke sath dikhata hai, area chart mein plot karke total profit ko emphasize kiya ja sakta hai.

**When to use area charts**

- To show volume data trends across time series.
- To represent single or dual data series showing the countable dataset.

**Kab basic area chart use karna chahiye?**  
Basic area charts behtareen hotay hain:

- volume trend ko waqt ke silsile mein dekhne aur muqablay ke liye.  
- ek individual series ke liye jo physically countable set ko represent karta hai.

- **Purpose**  
  Line chart + area fill for emphasis.
  
- **Real-World Example:**  
  Cumulative sales growth, rainfall trends over years.
  
- **When to Use:**  
  Jab aapko trend ke saath total volume ka emphasis dena ho.

## 5. **Stacked Bar / Column Chart**

- **Purpose:**  
  Categories ke andar sub-categories ka breakdown dikhana.
  
- **Real-World Example:**  
  Sales by region broken into product lines.
  
- **When to Use:**  
  Jab ek hi axis pe total aur breakdown dono chahiye.

**Stacked Bar Chart kab use karna chahiye Power BI mein?**

<img width="511" height="293" alt="stacked-bar-example-1" src="https://github.com/user-attachments/assets/02137c40-3505-4081-9836-4da258fdc1b9" />

Stacked Bar Chart tab use karna chahiye jab aapko mukhtalif categories ke andar sub-categories ke data ko ek saath compare karna ho. Yeh chart categories ke andar har hisay (part) ko alag rang se dikhata hai, taake aap total ke saath-saath har hisay ka contribution bhi dekh saken.

Misal ke taur par, agar aapko alag-alag sales regions mein different products ki sales ka muqabala karna ho, to stacked bar chart se aap asani se har region mein har product ki sales aur total sales dono ko visualize kar sakte hain.

**Column Chart kab use karna chahiye Power BI mein?**

![column-chart-1-simple-column](https://github.com/user-attachments/assets/e97e05ab-7f41-450f-bd20-d23a3c3eacf6)

Column chart tab use karna chahiye jab aapko alag-alag categories ke darmiyan quantitative values ka muqabala karna ho. Yeh chart vertical bars ke zariye har category ki value ko dikhata hai, jo comparison ko bohat asaan banata hai.

Misal ke taur par, agar aapko alag-alag shahron ki monthly sales dikhani ho, to column chart use karke aap asani se har shehar ki sales ko compare kar sakte hain.

## 6. **Clustered Bar / Column Chart**

- **Purpose:**  
  Multiple categories side-by-side compare karna.
  
- **Real-World Example:**  
  Year-wise sales comparison for two different products.
  
- **When to Use:**  
  Jab sub-groups ka direct comparison karna ho.

**Clustered Bar Chart kab use karna chahiye Power BI mein?**

![Clustered-Bar-Chart](https://github.com/user-attachments/assets/e6d0e757-739a-4a4e-838c-938ea027e551)

Clustered Bar Chart tab use karna chahiye jab aapko multiple categories ke andar sub-categories ko side-by-side compare karna ho. Yeh chart horizontal bars use karta hai, aur har category ke andar sub-categories ke bars ek saath clustered (grouped) hote hain taake asani se comparison ho sake.

Misal ke taur par, agar aapko alag-alag sales regions mein mukhtalif products ki sales ko compare karna ho, to clustered bar chart se aap asani se har region mein har product ki sales ko ek nazar mein dekh sakte hain.

## 7. **Scatter Plot**

- **Purpose:**  
  Do variables ke beech relationship dikhana.
  
- **Real-World Example:**  
  Advertising spend vs sales, temperature vs ice cream sales.
  
- **When to Use:**  
  Jab correlation ya trend between two metrics check karna ho.

**Scatter Plot kab use karna chahiye Power BI mein?**

<img width="660" height="409" alt="HowToCreateAScatterChart6-660x409" src="https://github.com/user-attachments/assets/ff26a1b9-c9e9-43c6-aa98-2f2cd1ba0f78" />

Scatter plot tab use karna chahiye jab aap do numerical variables ke darmiyan relationship ya correlation dekhna chahte hon. Yeh chart data points ko x aur y axis par plot karta hai, jisse aap patterns, trends, ya clusters asani se identify kar sakte hain.

Misal ke taur par, agar aapko sales aur advertising kharch ke darmiyan rishta dekhna ho, to scatter plot se aap samajh sakte hain ke zyada advertising kharch karne se sales barhti hain ya nahi.


## 8. **Map Visuals**

- **Purpose:**  
  Geographic data visualize karna.
  
- **Real-World Example:**  
  Sales by country, crime incidents by city.
  
- **When to Use:**  
  Jab data me location dimension ho (city, country, coordinates).

**Map Visuals kab use karna chahiye Power BI mein?**

<img width="720" height="380" alt="8-4-720x380" src="https://github.com/user-attachments/assets/60aab4d6-1a58-4149-a0b7-785b392e9ea6" />

Map visuals tab use karna chahiye jab aapko geographic data ko visualize karna ho, jaise ke locations, regions, ya countries ke hisaab se data ko dikhana ho. Yeh visuals location-based insights aur patterns samajhnay mein madad karte hain.

Misal ke taur par, agar aapko alag-alag shahron ya countries mein sales data dikhana ho, to map visual use karke aap asani se dekh sakte hain ke kahan zyada sales ho rahi hain aur kahan kam.

## 9. **Table**

- **Purpose:**  
  Detailed raw data dikhane ke liye.
  
- **Real-World Example:**  
  Invoice list, order details.
  
- **When to Use:**  
  Jab detailed record-level data chahiye.

**Table kab use karna chahiye Power BI mein?**

![Power-bi-conditional-formatting-only-data-bar-in-table-visual](https://github.com/user-attachments/assets/d9bef70c-8878-4937-bc19-8dce3219b196)

Table visual tab use karna chahiye jab aapko apne data ko rows aur columns mein detail ke sath dikhana ho. Yeh sabse seedha aur asaan tariqa hai jisme aap multiple fields ko organize karke clear aur structured format mein report bana sakte hain.

Misal ke taur par, agar aapko customer ka naam, unka phone number, aur unki total purchase value ek sath dikhani ho, to table visual bohat useful hota hai.

## 10. **Matrix**

- **Purpose:**  
  Table + pivot style summarization.
  
- **Real-World Example:**  
  Sales by product and by region in cross-tab format.

- **When to Use:**  
  Jab row aur column grouping chahiye.

**Matrix kab use karna chahiye Power BI mein?**

<img width="482" height="301" alt="ColumnWidthPicture1" src="https://github.com/user-attachments/assets/36a22c13-72d7-4dd7-8e2d-e8fe7e09dd55" />

Matrix visual tab use karna chahiye jab aapko apne data ko rows aur columns dono mein categories ke hisaab se group karke summarize karna ho. Yeh table se zyada flexible hota hai kyun ke aap rows ya columns ko expand ya collapse kar sakte hain (drill down/drill up), jis se detailed ya summarized view milti hai.

Misal ke taur par, agar aapko sales data ko region ke mutabiq aur uske andar product category ke mutabiq dikhana ho, to matrix visual bohat faida mand hota hai.

### Table aur Matrix mein Farq

- **Table Visual:**  
  Table ek simple grid hota hai jisme rows aur columns mein data dikhaya jata hai. Har row ek record ko represent karta hai aur har column ek field. Table mein grouping ya summarization nahi hoti; bas raw data dikhaya jata hai.

- **Matrix Visual:**  
  Matrix table ki tarah hota hai lekin zyada flexible aur powerful hota hai. Isme aap rows aur columns dono ko categories ke hisaab se group kar sakte hain, aur data ko summarize bhi kar sakte hain. Matrix mein aap rows ya columns ko expand ya collapse (drill down/up) bhi kar sakte hain, jis se detailed ya summarized view milti hai.

---

### Kab kaun sa use karna chahiye?

- **Table use karein:**  
  Jab aapko apna data seedha aur simple format mein, bina grouping ke, row-wise detail chahiye ho. Jaise customer list, transactions, ya kisi bhi data ka raw form.

- **Matrix use karein:**  
  Jab aapko data ko summarize karna ho, multiple dimensions mein grouping karni ho, ya drill down/up ki zarurat ho. Jaise sales ko region aur product category ke mutabiq dikhana.

---

### Example:

- Table:  
  Customer Name | Phone Number | Total Purchase  
  ---|---|---  
  Ali | 1234567890 | 5000  
  Sara | 0987654321 | 7000  

- Matrix:  
  | Region | Product Category | Total Sales |  
  |--------|------------------|-------------|  
  | Punjab | Electronics      | 100000      |  
  | Punjab | Furniture        | 50000       |  
  | Sindh  | Electronics      | 80000       |  

---

**Summary:**  
Table zyada raw aur simple data dikhata hai, jabke matrix grouping aur summarization ke sath zyada analytical view deta hai.

## 11. **Gauge**

- **Purpose:**  
  Target vs actual performance dikhana.
  
- **Real-World Example:**  
  KPI achievement %, sales target completion.
  
- **When to Use:**  
  Jab ek single value ka target ke against status highlight karna ho.

**Gauge visual kab use karna chahiye Power BI mein?**

<img width="384" height="186" alt="sample-gauge-chart" src="https://github.com/user-attachments/assets/ed9a8ceb-dec9-4a19-bae3-db978b3983b0" />

Gauge visual tab use karna chahiye jab aapko kisi single metric ko target ke against dikhana ho. Yeh visual progress ya performance ko ek dial/jahaz ki tarah show karta hai, jisse aap asani se samajh sakte hain ke aap apne goal ke kitne kareeb hain ya kitna door hain.

Misal ke taur par, agar aapko monthly sales target ke mukable mein current sales dikhani ho, to gauge visual use karke aap progress ko ek nazar mein dekh sakte hain.


## 12. **Card**

- **Purpose:**  
  Single numeric KPI highlight karna.
  
- **Real-World Example:**  
  Total sales, total profit, number of customers.
  
- **When to Use:**  
  Jab ek important metric ko prominent dikhana ho.

**Card visual kab use karna chahiye Power BI mein?**

<img width="2772" height="1765" alt="Optimizing-card-visuals-in-slow-Power-BI-reports-01" src="https://github.com/user-attachments/assets/2cc53020-1ffe-4f22-a575-d735cad108b4" />

Card visual tab use karna chahiye jab aapko kisi ek important metric ya value ko highlight karna ho. Yeh simple aur clear tarike se ek number ya text ko bade font mein dikhata hai taake user ki nazar seedha us important figure par jaye.

Misal ke taur par, agar aapko total sales, total customers, ya average profit jaisi key values dikhani ho, to card visual bohat effective hota hai.

## 13. **KPI Visual**

- **Purpose:**  
  Target vs actual with trend indicator.
  
- **Real-World Example:**  
  Monthly sales with target and arrow showing growth.
  
- **When to Use:**  
  Jab progress + trend dono ek sath dikhane ho.

**KPI Visual kab use karna chahiye Power BI mein?**

<img width="441" height="149" alt="Picture1" src="https://github.com/user-attachments/assets/5ec80523-51a8-4ca2-b2ba-bfd7a7e3b6cc" />

KPI (Key Performance Indicator) visual tab use karna chahiye jab aapko kisi important metric ki current value ko uske target ke saath compare karna ho, aur performance ka quick status dikhana ho. Yeh visual aksar arrow ya color coding (jaise green, red) use karta hai taake pata chale ke target achieve hua hai ya nahi.

Misal ke taur par, agar aapko monthly sales ko sales target ke saath compare karna ho, to KPI visual se aap asani se samajh sakte hain ke sales target cross hua hai ya nahi, aur kitna farq hai.

### KPI aur Card mein Farq

- **Card Visual:**  
  Card sirf ek single value ko dikhata hai, jaise total sales, total customers, ya average profit. Yeh bas value show karta hai bina kisi comparison ya context ke.

- **KPI Visual:**  
  KPI visual ek important metric ko uske target ya goal ke saath compare karta hai. Isme aapko pata chalta hai ke aap apne target ke kareeb hain ya nahi, aur performance ko arrows, colors (green, red), ya percentage changes ke zariye show karta hai.

---

### Simple Example:

- Card:  
  *Total Sales = 100,000*  

- KPI:  
  *Total Sales = 100,000* (Target 120,000) → Green arrow (agar target cross hua) ya red arrow (agar nahi hua)

---

**Summary:**  
Card sirf number dikhata hai, jabke KPI number ke saath uski performance ya progress bhi dikhata hai.

## 14. **Funnel Chart**

- **Purpose:**  
  Sequential process me drop-off dikhana.
  
- **Real-World Example:**  
  Sales pipeline stages, website conversion steps.
  
- **When to Use:**  
  Jab step-by-step process me conversion rate samajhna ho.

**Funnel Chart kab use karna chahiye Power BI mein?**

<img width="343" height="229" alt="power-bi-funnel-hover" src="https://github.com/user-attachments/assets/e40ae16e-1c61-4395-ba6f-30bc264925a3" />

Funnel chart tab use karna chahiye jab aapko process ke different stages mein data ka flow aur drop-off dikhana ho. Yeh chart stages ko ek funnel ki shape mein dikhata hai jisme upar se data zyada hota hai aur neeche jate jate kam hota hai, taake aap dekh saken ke process ke kis stage par sab se zyada log ya items drop ho rahe hain.

Misal ke taur par, agar aapko sales pipeline dikhani ho jisme leads se lekar final sales tak har stage par kitne prospects hain, to funnel chart use karna bohat faida mand hota hai.

## 15. **Treemap**

- **Purpose:**  
  Hierarchical data ko proportion ke sath dikhana.
  
- **Real-World Example:**  
  Product category share in sales, expense breakdown.
  
- **When to Use:**  
  Jab hierarchy + proportion ek sath show karna ho.

**Treemap kab use karna chahiye Power BI mein?**

<img width="382" height="219" alt="power-bi-treemap-overview" src="https://github.com/user-attachments/assets/c6afaf8a-017d-4899-999b-adcbffe105be" />

Treemap tab use karna chahiye jab aapko hierarchical data ko ek compact aur visual tareeke se dikhana ho. Yeh chart rectangles ke andar rectangles dikhata hai jisme har rectangle ki size aur rang uske data ke hisaab se hoti hai. Is se aap asani se data ke parts aur unka relative size samajh sakte hain.

Misal ke taur par, agar aapko apni company ke different departments ke revenue ka breakdown dikhana ho, to treemap se aap samajh sakte hain ke konsa department kitna bada hissa rakhta hai total revenue mein.

## Visual Selection Tips:

- **Trend chahiye →** Line Chart / Area Chart
- **Comparison chahiye →** Bar / Column Chart
- **Proportion chahiye →** Pie / Donut / Treemap
- **Relationship check karna ho →** Scatter Plot
- **Geographic data →** Map Visuals
- **Detail view →** Table / Matrix
- **Target tracking →** Gauge / KPI / Card
- **Process flow →** Funnel Chart

#  12 Dashboard Design Tips for Better Data Visualization

1. **Purpose samjho** – Pehle yeh samjho ke dashboard kis liye ban raha hai  
   *Example*: Agar sales dashboard bana rahe ho to decide karo ke yeh management ko monthly targets check karne ke liye hai ya sales team ko daily performance monitor karne ke liye  

2. **Sirf important content rakho** – Har cheez mat dikhayo, sirf woh jo kaam ka ho  
   *Example*: Agar inventory dashboard hai to sirf fast-moving aur slow-moving products ka data dikhayo, puri product list nahi  

3. **Data ink ratio ka khayal rakho** – Fazool graphics ya decorations hatao jo data samajhne me help nahi karte  
   *Example*: Bar chart me unnecessary 3D effects use karne ki bajaye simple 2D bars rakho  

4. **Numbers round karo** – Data ko readable banane ke liye round figures use karo  
   *Example*: Revenue ko 1,254,873 likhne ke bajaye 1.25M likho taake management jaldi samajh sake  

5. **Best visualization choose karo** – Har data ke liye best chart select karo  
   *Example*: Market share dikhane ke liye pie chart use karo lekin sales trend dikhane ke liye line chart  

6. **Related metrics group karo** – Jo metrics related hain unko ek saath rakho  
   *Example*: Sales amount, profit margin, aur units sold ko ek hi section me dikhayo  

7. **Consistency rakho** – Same type ke data ke liye same style ka visualization use karo  
   *Example*: Agar regions ke sales bar chart me dikhate ho to saare regions ke liye bar chart hi use karo, kisi ek ke liye pie chart mat lagao  

8. **Hierarchy dikhayo** – Important metrics ko zyada highlight karo  
   *Example*: Dashboard ke top par total revenue aur profit rakho, niche category wise breakdown  

9. **Numbers ko context do** – Sirf number na dikhayo, comparison bhi dikhayo  
   *Example*: Agar profit 2M hai to previous month ke profit ke sath arrow lagao jo increase ya decrease show kare  

10. **Clear labels use karo** – Har metric ka naam clear likho  
    *Example*: “Total Sales” likho sirf “Sales” nahi, aur time frame bhi add karo jaise “Total Sales (Jan 2025)”  

11. **Logon ke liye banao** – Rules tod sakte ho agar use improve hota ho  
    *Example*: Agar management ko ek hi page me sab kuch dekhna pasand hai to multiple metrics ek page pe arrange kar do chahe best practice alag ho  

12. **Evolve karte raho** – Dashboard ko feedback ke basis pe update karo  
    *Example*: Agar sales team ke kehne pe discount ka column add karne se unka kaam easy ho jata hai to woh feature add kar do  

#  Introduction to data models

As a data analyst, aapko bohot zyada records manage karne padte hain (hazaron ya lakhon tak). Insights hasil karne ka behtareen tareeqa ye hai ke raw data ko data models me convert kiya jaye.  

Data model ka kaam hota hai alag alag data sources (jaise sales, customers, marketing) ko ek jagah combine karna, taake unse useful visualizations aur analysis kiya ja sake.  

Power BI ek tool hai jahan aap data models bana sakte hain, relationships define kar sakte hain (jaise Customer ID ke zariye sales aur customer tables ko link karna), data types assign kar sakte hain, aur calculated columns & measures create kar sakte hain using DAX.  

Data modeling ke main steps:  
1. Data sources se connect hona  
2. Data ko clean aur transform karna  
3. Tables aur columns ka structure set karna  
4. Relationships define karna  
5. Measures aur calculated columns create karna (DAX)  

Achhi data modeling se reports fast hoti hain, data aggregation easy hota hai (hierarchies ke saath), aur advanced analytics possible hota hai (complex measures, predictive analysis).  

Example: Adventure Works ne apne customers, sales, aur marketing data ko ek model me combine kiya, relationships set kiye aur DAX calculations banayi, jis se pata chala kaunsi campaigns ne sales boost ki.  

Conclusion: Data model foundation hota hai aapke analysis ka. Agar ye structured aur optimized ho, to insights accurate aur reliable milte hain.

**Power BI Model View**  
Reports ke andar data models banane aur manage karne ke liye use hota hai. Ye tables, relationships aur columns ka visual overview deta hai, jo complex relationships samajhne me help karta hai.  

**Access**: Left sidebar me model icon click karo.  

**Main UI elements**:  
1. Diagram view (Canvas)  
2. Data pane  
3. Properties pane  
4. Home ribbon  

**Diagram view (Canvas)**:  
- Data model ka visual map hota hai (tables, fields, relationships)  
- Data tables raw data ko represent karti hain (imported ya calculated)  
- Table expand/collapse karke fields dekh sakte ho  
- Eye icon se table ko report me hide kar sakte ho (model me rahegi aur calculations me use ho sakti hai)  

<img width="1430" height="804" alt="1" src="https://github.com/user-attachments/assets/cb3f8f6a-6b4f-427a-b9a0-92fc6a27f0a5" />

To access more options for a table, click the ellipses (three dots) beside the eye icon, which allows you to rename, delete, or perform other actions on the table.

<img width="1430" height="804" alt="2" src="https://github.com/user-attachments/assets/d8d74654-13c7-4b71-888e-808fdb881caf" />

**Fields**

Fields are columns within your data tables, representing individual data points or attributes.In the Model view, these fields are listed under their respective tables. All calculated columns and measures also appear as fields in the data tables.

<img width="1430" height="804" alt="3" src="https://github.com/user-attachments/assets/7420d559-5c09-4205-8b25-1b79a042d6ed" />

**Relationships**  
Model View ka ek main feature ye hai ke tables ke beech relationships banaye aur manage kiye ja sakte hain.  

- Power BI aksar automatically relationship detect kar leta hai agar common fields (same naam wale columns) mil jaen  
- User manually bhi relationship bana ya edit kar sakta hai  
- Relationship banane ka base common key fields hoti hain (jaise CustomerID in Customers table aur Orders table)  

<img width="1430" height="804" alt="4" src="https://github.com/user-attachments/assets/243d54b9-cb12-4671-af85-a8604626c0aa" />

**Relationships ka Visual**  
- Tables ke beech ek connector line hoti hai jo relationship dikhati hai  
- Line par hover karo to wo fields highlight hoti hain jo relationship bana rahi hain  
- Line par arrow cross-filter direction batata hai (data kis table se kis table me flow kar raha hai)
  
<img width="1430" height="804" alt="5" src="https://github.com/user-attachments/assets/cb83c855-773f-47ed-a29b-7424074e9de9" />

The 1 icon represents the “one” side of the relationship, while the * icon indicates the “many” side.

<img width="1430" height="804" alt="6" src="https://github.com/user-attachments/assets/e12e0eac-b36f-48cf-8718-9ee099e52f9c" />

To modify a relationship, double-click the connector line to open the Edit Relationship window, where you can configure or change relationship settings.

<img width="1430" height="804" alt="7" src="https://github.com/user-attachments/assets/9fa465f6-c6e1-4b4c-9155-a90c5a48f887" />

**Data Pane**  
- Power BI Desktop ke teeno views (Report, Data, Model) me common hota hai  
- Saare data tables aur unke fields list karta hai (calculated tables, columns, measures included)  
- Agar bohot zyada tables ho to search bar use karke specific table dhoond sakte ho  

<img width="1430" height="803" alt="8" src="https://github.com/user-attachments/assets/d31e1eda-3fd3-4335-aa3f-dd6056780c6d" />

You can also expand or collapse the data pane by selecting the double arrow.

<img width="1430" height="803" alt="9" src="https://github.com/user-attachments/assets/5596725b-7655-428c-be52-fff49ddb9e1f" />

**Properties Pane**  
- Tables aur columns ki properties edit aur configure karne ke liye use hota hai  
- Do sections hote hain:  
  1. **General**: Table/field rename karna, description add karna, basic settings adjust karna  
  2. **Advanced**: Detailed configurations jaise column features enable/disable karna  

<img width="1430" height="804" alt="10" src="https://github.com/user-attachments/assets/40655367-ea92-4c89-b8e6-fa3f780b0098" />

**Home Ribbon (Model View)**  
- Data ko shape aur structure karne ke liye functions provide karta hai  
- Reports aur visualizations banane se pehle data preparation ke liye use hota hai  
- Functions group form me arranged hote hain (jaise table manage karna, relationships set karna, fields modify karna)  

<img width="1430" height="804" alt="11" src="https://github.com/user-attachments/assets/3f9fe931-0066-4ac5-b3c1-ea99fd1129bb" />

**Data (Home Ribbon)**  
- Report view aur Data view ki tarah connectivity options deta hai  
- New data sources connect karne ya existing ko manage karne ke liye use hota hai  

<img width="1430" height="804" alt="12" src="https://github.com/user-attachments/assets/ca361cd2-bdb1-4909-b344-a860bbec8410" />

**Queries (Home Ribbon)**  
- **Transform data**: Power Query Editor open karta hai jahan data cleaning aur transformations ki ja sakti hain  
- **Refresh**: Dataset ko source se latest data ke sath update karta hai  

<img width="1430" height="804" alt="13" src="https://github.com/user-attachments/assets/9bc42b5f-d763-4304-af8a-9acfb0bd1651" />

**Manage Relationships**

This tool allows you to establish new relationships between tables or edit existing ones.

<img width="1430" height="804" alt="14" src="https://github.com/user-attachments/assets/959c5237-0785-447d-8f7e-53daa85c3a33" />

**Calculations (Home Ribbon)**  

- Custom calculations banane ka option deta hai jaise calculated tables, columns aur measures  
- Ye calculations **DAX (Data Analysis Expressions)** ka use karke banti hain jo analysis capabilities ko enhance karti hain  

<img width="1430" height="804" alt="15" src="https://github.com/user-attachments/assets/95fcd6f9-d25e-4b62-870a-15aa521740bc" />

**Security (Home Ribbon)**  
- Roles aur rules define karne ka option deta hai taake data access control kiya ja sake  
- Isse Power BI Desktop me security aur user management improve hota hai  

<img width="1430" height="804" alt="16" src="https://github.com/user-attachments/assets/f9744867-2f2c-40c1-bc23-a52ed2205d94" />

**Q&A**

- A natural language query tool that lets you interact with your data by asking questions in everyday language.

<img width="1430" height="804" alt="17" src="https://github.com/user-attachments/assets/129ebc14-1fa3-493c-b209-024da4cec918" />

**Share (Home Ribbon)**  
- Reports share karne ka option deta hai taake team members ke sath collaborate kiya ja sake  
- Isse teamwork aur report sharing process streamline hoti hai  

<img width="1430" height="804" alt="18" src="https://github.com/user-attachments/assets/47000a88-bde5-406f-90ca-b6ba319d3c88" />

**Conclusion**  

- Model view UI aur uske components ka achhi tarah use seekhna data modeling, schema design aur advanced Power BI features ke liye bohot zaroori hai  
- In tools ko master karne se aap structured aur insightful data models bana sakte ho jo reporting capabilities ko enhance karte hain  

#  Introduction to schemas

Business insights generate karna ka matlab hota hai bohot saare data ko analyze karna aur is data ka sahi tarike se store aur structure karna bohot important hota hai. Power BI me aap apne data ko schema ka use karke structure kar sakte hain. Schema data ka ek logical framework hota hai jo batata hai ke data kaise organize aur connect kiya gaya hai.

**Adventure Works** apne inventory ko optimize karna chahta hai aur sales strategy ko improve karke zyada bicycles sell karna chahta hai. Iske liye wo apne customer, product, sales data aur business ke doosre areas ka data analyze karega. Power BI schema use karke wo in data sources ke beech relationships banayega taake required insights generate kiye ja sakein.

## Schema ki Types

### 1. Flat Schema

- **Definition**: Sab attributes aur fields ek hi table me store hote hain.
  
- **Advantages**:
  
  - Data retrieval easy hoti hai
  - Analysis simple hota hai
  - Visualization straightforward hoti hai
    
- **Disadvantages**:
  - Large datasets ke liye inefficient
  - Data redundancy aur inconsistency
  - Complex datasets ke liye suitable nahi

### 2. Star Schema

- **Definition**: Ek central fact table hota hai jo multiple dimension tables se connect hota hai, jiska structure star shape ka hota hai.
- **Example**: Sales transactions fact table connect hoti hai customers, employees, dates, marketing campaigns dimension tables se.

- **Advantages**:
  
  - Data redundancy kam hoti hai
  - Query performance better hota hai
  - Logical aur clear data model
    
- **Disadvantages**:
- 
  - Tables add/modify karna mushkil
  - Complex relationships handle karna limited

### 3. Snowflake Schema

- **Definition**: Star schema ka extended form, jisme dimension tables ko aur normalize karke related tables me tod diya jata hai.
- **Example**: Product table ko supplier aur category tables me todna.
- 
- **Advantages**:
  
  - Data storage aur retrieval efficient hota hai
  - Data integrity aur consistency improve hoti hai
  - Scalability aur flexibility zyada hoti hai

- **Disadvantages**:

  - Analysis complex ho jata hai
  - Relationships samajhna aur manage karna mushkil
  - Queries slow ho sakti hain

## Schema Validation

Schema validate karte waqt:

- Har column ka correct **data type** (text, numeric) assign ho
- Correct **formatting** applied ho
- Clear **descriptions** ho relevant context ke saath
- Table aur column properties correctly configured ho

## Conclusion

Different schema types samajhna aur unke advantages/disadvantages jaan lena data analysts ke liye bohot zaroori hai. Power BI me strong schema design karke aap apne data ki integrity maintain kar sakte hain aur meaningful insights generate kar sakte hain.








































