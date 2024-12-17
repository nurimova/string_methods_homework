
# **Xush kelibsiz**  
# **String usullari**  
Uy vazifalari va testlarni avtomatik tekshirish bo‘yicha qo‘llanma:  
- Ushbu repozitoriyani fork qiling  
- Masalalarni yeching  
- To‘g‘ri commit xabarlari bilan yuklang  

---

## **Masalalar**  

### **String01**  
Berilgan bir nechta so‘zlardan iborat satrda barcha harflar kichik yozilgan. Har bir so‘zning birinchi harfini katta harf bilan boshlash kerak.  

**Misol 1:**  
```Python
Input: a="google is a search engine"  
Output: "Google Is A Search Engine"  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String02**  
Berilgan kichik harflardan iborat bir nechta so‘zli satrni to‘liq katta harflarga o‘tkazing.  

**Misol 1:**  
```Python
Input: a="apple is a fruit"  
Output: "APPLE IS A FRUIT"  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String03**  
Barcha harflari katta bo‘lgan bir nechta so‘zli satr berilgan. Harflarni kichik harflarga o‘tkazing va qaytaring.  

**Misol 1:**  
```Python
Input: a="IPHONE IS A MOBILE"  
Output: "iphone is a mobile"  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String04**  
Berilgan satr o‘zgaruvchisi faqat kichik harflardan iborat ekanligini tekshiring.  

**Misol 1:**  
```Python
Input: a="itmarkaz"  
Output: True  
```  

**Misol 2:**  
```Python
Input: a="Mobile"  
Output: False  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String05**  
Berilgan bir nechta so‘zli satrni to‘liq bosh harf bilan boshlanadigan formatga o‘tkazing.  

**Misol 1:**  
```Python
Input: a="mobile development"  
Output: "Mobile development"  
```  

**Misol 2:**  
```Python
Input: a="python programming"  
Output: "Python programming"  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String06**  
Berilgan satr faqat raqamlardan iborat ekanligini tekshiring.  

**Misol 1:**  
```Python
Input: a="12345"  
Output: True  
```  

**Misol 2:**  
```Python
Input: a="2022ABC"  
Output: False  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String07**  
Berilgan satr faqat harflardan iborat ekanligini tekshiring.  

**Misol 1:**  
```Python
Input: a="12345"  
Output: False  
```  

**Misol 2:**  
```Python
Input: a="2022ABC"  
Output: False  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String08**  
Berilgan satr faqat katta harflardan iborat ekanligini tekshiring.  

**Misol 1:**  
```Python
Input: a="ITMARKAZ"  
Output: True  
```  

**Misol 2:**  
```Python
Input: a="Mobile"  
Output: False  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String09**  
Berilgan satrda `"a"` harfi necha marta uchrashganini toping.  

**Misol 1:**  
```Python
Input: a="google is a search engine"  
Output: 3  
```  

**Misol 2:**  
```Python
Input: a="Mobile development"  
Output: 0  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

### **String10**  
Berilgan satrda `"x"` harfi qaysi indeksda joylashganligini toping.  

**Misol 1:**  
```Python
Input: a="Mobile tpye xiomi"  
Output: 12  
```  

**Misol 2:**  
```Python
Input: a="iphone x is a mobile"  
Output: 7  
```  

**Cheklovlar:**  
- 2 <= length(a) <= 10^5  

---

# **Ogohlantirish**  
- Boshqalarning yechimlarini ko‘chirmang  
- Hech qanday qatorni o‘chirmang  

