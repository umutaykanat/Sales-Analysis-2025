# 🛒 2019 E-commerce Sales Analysis

Bu proje, 2019 yılına ait bir e-ticaret firmasının satış verilerinin analizini içermektedir.  
Amaç, satışların zamansal dağılımını, şehir bazlı ürün tercihlerindeki farklılıkları ve en çok satılan ürünleri belirlemektir.  

---

## 📂 Veri Seti
Veri seti, 2019 yılına ait 12 aylık sipariş bilgilerini içermektedir.  

**Değişkenler:**
- `Order ID`: Sipariş ID numarası  
- `Product`: Sipariş edilen ürün  
- `Quantity Ordered`: Sipariş edilen ürün adedi  
- `Price Each`: Ürün birim fiyatı  
- `Order Date`: Sipariş tarihi  
- `Purchase Address`: Siparişin yapıldığı adres  

📌 Veri seti burada **örnek olarak bir alt küme** paylaşılmıştır. 

---

## 🔧 Kullanılan Teknolojiler
- Python (3.9+)  
- pandas  
- numpy  
- matplotlib  
- seaborn  

---

## 📊 Analizden Elde Edilen Bulgular
- **En çok satan ürünler**: Pil paketleri (AA ve AAA), şarj kabloları (USB-C, Lightning).  
- **En çok satış yapılan ay**: Aralık (tatil sezonu).  
- **En çok satış yapılan şehirler**: New York, Los Angeles ve San Francisco.  
- **Fiyat & adet ilişkisi**: Düşük fiyatlı ürünler daha yüksek adetlerde satılmıştır.  

---

## 🚀 Gelecek Çalışmalar
- Müşteri segmentasyonu (şehir bazlı / ürün tercihine göre).  
- Satış tahmin modelleri (zaman serisi / makine öğrenmesi).  
- İnteraktif dashboard geliştirme (Plotly, Dash, Streamlit).  

---

## 📌 Notebook
Tüm analiz adımlarına buradan ulaşabilirsiniz:  
👉 [sale_analysis.ipynb](notebooks/sale_analysis.ipynb)  

---

## ⚙️ Çalıştırma
```bash
# Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt
