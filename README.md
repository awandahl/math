# Math databases

A simple resource page for a workshop about getting started with the two major bibliographic databases in mathematics.

#### How to access:

**zbMATH:** https://zbmath.org/  | zbMATH a.k.a. zbMATH Open *is open for everyone to search*    
**MathSciNet:** https://mathscinet.ams.org   |   Off campus go [here](https://focus.lib.kth.se/login?URL=https://www.ams.org/mathscinet/)     
**MathSciNet new beta interface:** https://mathscinet.ams.org/mathscinet/beta/publications-search   |   Off campus go [here](https://focus.lib.kth.se/login?url=https://mathscinet.ams.org/mathscinet/beta/publications-search)

---

#### Handouts   

ETH Zürich has very good handouts covering these databases:    

[Introduction to the database zbMATH Open – Zentralblatt MATH](https://github.com/awandahl/math/blob/main/ETH_2022-03-11-ZentralblattMATH_Handout_EN.pdf)    
[Introduction to the database MathSciNet – Mathematical Reviews](https://github.com/awandahl/math/blob/main/ETH_2022-03-11-MathSciNet_Handout_EN.pdf)

MathSciNet has a new beta interface coming up soon:    

[MathSciNet beta Quick Start Guide](https://www.ams.org/publications/msn-quickstart-guide.pdf)

---
### About

**zbMATH:** "Currently, zbMATH Open contains around **4.4 million** bibliographic entries with reviews or abstracts drawn from more than 3,000 journals and book series, and some 190,000 books. Our coverage, which starts in the 18th century, is complete from 1868 to the present day..."    

**MathSciNet:** "MathSciNet® contains over **3.6 million** items and over 2.3 million direct links to original articles. Bibliographic data from retrodigitized articles dates back to the early 1800s. Reference lists are collected and matched internally from approximately 650 journals, and citation data for journals, authors, articles and reviews is provided..."    

---

### 1. Simple search  

#### Searching **without** quotation marks = the words in any order:    


*climate change*    

#### Results    
**zbMATH:** 1168    
**MathSciNet beta:** 905    

#### Searching **with** quotation marks = the words as a phrase:    

*"climate change"* 

#### Results
**zbMATH:** 996    
**MathSciNet beta:** 695    

---

### 2. Mathematics Subject Classification (MSC)
MSC results for "climate" from *searching the classification scheme* in [zbMATH](https://zbmath.org/classification/) or [MathSciNet](https://mathscinet-ams-org.focus.lib.kth.se/mathscinet/beta/msc-search)    

````
86 (1940-now) Geophysics [See also 76U05, 76V05]    
	86A (1980-now) Geophysics [See also 76U05, 76V05]    
		**86A08** (2020-now) Climate science and climate modeling    
````

#### Searching for 86A08    

#### Results
**zbMATH:** cc:86A08 = 223    
**MathSciNet beta:** pc:"86A08" OR sc:"86A08" = 242  

---
### 3. Advanced search    

a) *I want to find documents about the climate change and how it affects the oceans*        

My example:    

**zbMATH:**  any:ocean* & cc:86A08  = 58    
**MathSciNet beta:** *see below*

*Parentheses matters:*    
pc:"86A08" OR sc:"86A08" AND any:(ocean*) = 169    
(pc:(86A08) OR sc:(86A08)) AND any:(ocean*) = 86    
  

b) *I want to find documents about [tropical geometry](https://en.wikipedia.org/wiki/Tropical_geometry)*

**zbMATH:** cc:14T90 | ab:"tropical geometr*" = 447    
**MathSciNet beta:** pc:(14t90) OR sc:(14t90) OR r:("tropical geometr*") = 438

---
### 4. Searching for an author    

*Sandra Di Rocco*    
- Publications
- Co-authors
- Citations
- Reviews

---
 
