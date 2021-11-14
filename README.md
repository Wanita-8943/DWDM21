Data Warehouse & Data Mining 2021

Wanita Somdej 623020536-5

กลุ่ม แมวส้มสร้างตัว 🐈

***1 วานิตา สมเด็จ***

2 กรกนก สังฆพันธ์

3 คำแสน แก้วพิภพ

4 จิตรกร จันทะสี 

5 อาธิติยา ธรรมวงษา

# สารบัญ

* บทที่ 1 Introduction
  * [Lecture Introduction](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter1.pdf)
    * Why Data Mining?    
    * What is Data Mining?    
    * Knowledge Discovery (KDD) Process     
    * Data Mining Functions	       
       * Pattern Discovery	       
       * Classification       
       * Cluster Analysis
* บทที่ 2 Getting to Know Your Data
  * [Lecture Data Objects and Attribute Types](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter2.pdf)
    * Types of Data Sets
       * Record Data
       * Graphs and Networks
       * Ordered Data
       * Spatial, image and multimedia Data
    * Important Characteristics of Structured Data 		
    * Data Objects
    * Attributes
    * Attribute Types
    * Numeric Attribute Types
    * Basic Statistical Descriptions of Data
  
  * [Basic Python](https://github.com/Wanita-8943/DWDM21/blob/main/Data101(Chapter2).ipynb)
    * Casting int() float() str() 
    * Data Structure 
      * string คือ list ของตัวหนังสือ
      * วิธีสร้าง list ว่าง
         * การเติมค่าเข้าใน list (.append()) 
         * การชี้ค่า list (indexing) 
      * list slicing 
      * list+list 
      * format string
    * Loop 
      * Nested loop 
    * Condition (if statement) 
      * Quiz 1 หา min 
      * HW ตัดเกรด 
    * Function 
      * Example1 
      * Example2 (ไม่มี input) 
      * Example 3 (ไม่มี output) 
      * Example 4 (ไม่มี input และ output)
      * ลักษณะของ input(paremeter,argument)
      * Quiz 2
  
  * [Pandas](https://github.com/Wanita-8943/DWDM21/blob/main/Data102_(Chapter2).ipynb)
    * Read Data
      * .head() .tail() 
    * Box plot
    * Time Series Plot
  
  * [Visualization](https://github.com/Wanita-8943/DWDM21/blob/main/Data_Visualization.ipynb)
    * Scatter plot
    * Plot
    * Quiz กลุ่ม III วาดภาพที่มี marker เป็น สี่เหลี่ยมจัตุรัส เส้นเป็นเส้นประสลับจุดไข่ปลา สีฟ้าอ่อน
    * Bar Chart กราฟแท่ง
      * Grouped Barchart ใช้เปรียบเทียบกลุ่มย่อยในกลุ่มใหญ่
      * Stacked Barchart เปรียบเทียบข้ามกลุ่ม
    * Histogram
  
  * [Distance_Numpy](https://github.com/Wanita-8943/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy array
      * สร้าง numpy array (matrix) จาก list
        * matrix transpose
      * สร้าง matrix เริ่มต้น (zeros, ones)
      * สร้าง matrix random
        * matix properties
      * Indexing&Slicing
      * Useful functions
      * วนลูปเอง
        * summatiom รวมค่าทุกค่าในarray
    * Distance Matrix
      * Euclidean Distance (L2-norm)
      * Distance function
      * Manhattan Distance (L1-norm)
      * quiz6
      * HW11
      * Distance of Binary Value
      
* บทที่ 3 Data Preprocessing
  
  * [Data Preprocessing](https://github.com/Wanita-8943/DWDM21/blob/main/Data_Preprocessing(Chapter_3).ipynb)
    * Meta Data (Data ที่ใช้อธิบาย Data)
    * ชี้ข้อมมูลในตาราง
      * ชี้แบบธรรมดาใช้ [ชื่อคอลัมน์][ชื่อindex]
      * ชี้แบบ .iloc[] (มองข้อมูลเป็นเมทริกซ์)
    * Missing Values
      * Missing Values กำจัดmissing 
      * Handling Missing Value 1 (ลบค่า missing)
      * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน คอลัมล์ที่เราสนใจเท่านั้น)
      * Handling Missing Value 2 (แทนค่าด้วย class ใหม่ (unknown))
      * Handling Missing Value 3 (แทนค่าด้วย class ใหม่ (ค่าที่เหมาะสม))
      * Handling Missing Value 4 (แทนค่าด้วย ค่ากลาง)
        * ถ้าเป็น numeric ใช้ mean
        * ถ้าเป็น numeric (ตัวหนังสือ) ใช้ mode
        * ถ้าเป็น ordinal ใช้ median
      * Handling Missing Value 5 (แทนค่าด้วย ค่ากลาง ของ simple)
    * Select data by values [PD]
      * สร้าง list ของ boolean
        * นำ list ของ boolean มาเลือกค่าในตาราง
      * Quiz 4 + HW
      * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)(ต่อ)
      * การเรียงข้อมูล[PD]
    * Outlier
      * ตัด outlier แบบ manual
      * Pandas' looping (.iterrows)
    * การรวมตาราง Data Integration (ต่อตารางในแนวแกน x) 
      * รวม 2 ตาราง (.merge())
      * เลือกเฉพาะ column ที่ต้องการมาแปะ (.map())
      * ตารางรอง (ตารางข้างขวา) ต้องไม่มี index ซ้ำ
      * Group by (pandas)
      * [PD] save ตารางเอาไปใช้ที่อื่น
      * [PD] การสร้างตาราง      
    * [PD] การสร้างตาราง 
    * 
* บทที่ 4  Data Warehousing and On-line 

* บทที่ 5 Association Rules
  * [Lecture Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter6.pdf)
    * Basic Concepts
      * What Is Pattern Discovery?        
        * k-Itemsets and Their Supports
        * Frequent Itemsets (Patterns)   
        * From Frequent Itemsets to Association Rules     
        * Mining Frequent Itemsets and Association Rules
    * Efficient Pattern Mining Methods
      * Apriori Algorithm
        * Apriori Pruning and Scalable Mining Methods
        * A Candidate Generation & Test Approach     
        * The Apriori Algorithm   
  
  * [Data 'reduced_marketbasket' Case](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
    * มีประเทศสาขาของ supermaket นี้ทั้งหมดกี่ประเทศ
      * [HW13]
      * เฉลย[HW13]
    * ลบ recodes ที่ถูก cancel ออกไป
    * เตรียม Data สำหรับ (Fequence Pattern) Association Rule
    * Apriori
      * Quiz7      
      
* บทที่ 6 Classification
  * [Lecture Classification: Basic Concepts](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter%208%20(14:10:64).pdf)     
    * Basic Concepts
      * Supervised vs. Unsupervised Learning (1)
      * Supervised vs. Unsupervised Learning (2)
      * Prediction Problems: Classification vs. Numeric Prediction
      * Classification—Model Construction, Validation and Testing
    * Decision Tree Induction      
      * An Example
      * Information Gain
  
  * [HW Decision Tree คำนวณมือ](https://github.com/Wanita-8943/DWDM21/blob/main/Decision_tree.pdf)
  
  * [Decision Tree](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
    * Load Data
    * Train Model
      * import (เรียกใช้ algorithm algorithm ที่เราต้องการ)
      * define (กำหนด parameters ให้กับ model)
      * train (ฝึกสอนตัวแบบ)
    * Plot tree
    * Evalution
      * Random
    * Advanced Tree
    * TEST
    * Start here
      * Train - Test
      * Train - Validation 
    * HW
      * ต้นไม้ที่ใช้เกณฑ์ Entropy มีความสูงไม่เกิน 4 ชั้น
      * ต้นไม้ที่ใช้เกณฑ์ Gini มีใบไม่เกิน 25 ใบ
      * ต้นไม้ที่ใช้เกณฑ์ Entropy และใช้การ split แบบ random
      * ต้นไม้ที่เราคิดเอง
      
  * [Lecture k-Nearest Neighbor](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter%208%20(14:10:64).pdf)
    * Bayes’ Theorem: Basics
    * Naïve Bayes Classifier
      * Categorical vs. Continuous Valued Features
      * Training Dataset
    * Lazy Learner: Instance-Based Methods  
    * The k-Nearest Neighbor Algorithm
  
  * [k-Nearest Neighbor & Neural Networks](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter7Classification(KNN_NN).ipynb)
    * Losd data
    * Train Model
      * import
      * Knn1
      * Knn2
      * Knn3
    * Retrain & Evaluate 
    * Neural Network
      * import
      * Define
      * Train - Test
      * ANN2
      * ANN3
  
  * [Evaluation](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter7_Classification(Evaluation).ipynb)
    * Load data 
    * แบ่ง Data
    * สร้าง Model ทำนาย
      * import
      * Define
      * Train
      * Evaluation    
    
* บทที่ 7 Clustering
  * [Clustering](https://github.com/Wanita-8943/DWDM21/blob/main/Chapter8_Clustering.ipynb)
    * K-means
      * Generate Data
      * Explore data
      * Clustering
        * Import
        * Define
        * Fit-Predict
        * Plot
      * Example Application (Color Quantization) 
        * นับจำนวนสี 
        * จัดกลุ่มสีให้เหลือ 16 สี
        * แปลงข้อมูลให้อยู่ในรูป row-cocumn
        * ใช้ centroid เป็นตัวแทนของสี

* MiniExam
  * [MiniExam](https://github.com/Wanita-8943/DWDM21/blob/main/MiniExam.ipynb)
  
* Group Project  
  * [Group Project](https://github.com/Wanita-8943/DWDM21/blob/main/Group_Project.ipynb)
    * Data and Preprocessing
      * เว็บที่มาของข้อมูล
      * ตาราง sellers
      * ตาราง order_items
      * ตาราง products
      * เชื่อมต่อตาราง
    * ปัญหา
      * Association Rules
      * Classification 
        * ประโยชน์ของการทำนาย 
        * Split Data
        * Decision Tree
        * KNN
          * KNN1
          * KNN2
          * KNN3 
        * Neural Network
          * ANN1
          * ANN2
          * ANN3
          * พล็อตกราฟเปรียบเทียบความแม่นยำของการวัดผล         
        * Retrain & Evaluate
      * Visulization
        * เปรียบเทียบจำนวนสินค้าที่ขายได้ในแต่ล่ะ category
        * เปรียบเทียบ ราคา,ค่าส่ง,ความสูง,ความยาว,น้ำหนัก และ ความกว้าง เฉลี่ย ของแต่ล่ะ category
          * ราคาเฉลี่ยของแต่ล่ะ category
          * ค่าส่งเฉลี่ยของแต่ล่ะ category
          * ความสูงเฉลี่ยของแต่ล่ะ category
          * ความยาวเฉลี่ยของแต่ล่ะ category
          * น้ำหนักเฉลี่ยของแต่ล่ะ category
          * ความกว้างเฉลี่ยของแต่ล่ะ category
           
   *  [Slide นำเสนอ](https://github.com/Wanita-8943/DWDM21/blob/main/%E0%B8%99%E0%B8%B3%E0%B9%80%E0%B8%AA%E0%B8%99%E0%B8%AD_PROJECT_DWDM21.pdf)    
