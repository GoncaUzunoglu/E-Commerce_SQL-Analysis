# E-Commerce_SQL-Analysis
# SQL Capstone Project - Brazilian E-Commerce Public Dataset by Olist

## Proje Hakkında

Bu proje, Brezilya'nın önde gelen e-ticaret platformlarından biri olan Olist tarafından sağlanan veri setini kullanarak SQL analizi gerçekleştirmektedir. Amacımız, bu veri seti üzerinde çeşitli analizler yaparak anlamlı içgörüler elde etmektir.

## Veri Seti Hakkında

Olist veri seti, Brezilya e-ticaret işlemleriyle ilgili geniş ve detaylı bilgileri içermektedir. Veri seti, müşteri davranışları, siparişler, ürünler, ödemeler, incelemeler ve satıcılar gibi çeşitli bileşenleri kapsar.

### Veri Seti İçeriği

Veri seti aşağıdaki CSV dosyalarından oluşmaktadır:

1. **olist_customers_dataset.csv**:
    - `customer_id`: Müşteri kimliği (eşsiz)
    - `customer_unique_id`: Tekil müşteri kimliği
    - `customer_zip_code_prefix`: Müşterinin posta kodu
    - `customer_city`: Müşterinin şehri
    - `customer_state`: Müşterinin bulunduğu eyalet

2. **olist_orders_dataset.csv**:
    - `order_id`: Sipariş kimliği (eşsiz)
    - `customer_id`: Müşteri kimliği (eşsiz)
    - `order_status`: Sipariş durumu
    - `order_purchase_timestamp`: Siparişin verildiği zaman
    - `order_approved_at`: Siparişin onaylandığı zaman
    - `order_delivered_carrier_date`: Siparişin taşıyıcıya teslim edildiği tarih
    - `order_delivered_customer_date`: Siparişin müşteriye teslim edildiği tarih
    - `order_estimated_delivery_date`: Tahmini teslimat tarihi

3. **olist_order_items_dataset.csv**:
    - `order_id`: Sipariş kimliği
    - `order_item_id`: Sipariş öğesi kimliği
    - `product_id`: Ürün kimliği
    - `seller_id`: Satıcı kimliği
    - `shipping_limit_date`: Gönderim son tarihi
    - `price`: Ürün fiyatı
    - `freight_value`: Nakliye ücreti

4. **olist_products_dataset.csv**:
    - `product_id`: Ürün kimliği (eşsiz)
    - `product_category_name`: Ürün kategorisi
    - `product_name_lenght`: Ürün adı uzunluğu
    - `product_description_lenght`: Ürün açıklaması uzunluğu
    - `product_photos_qty`: Ürün fotoğraf sayısı
    - `product_weight_g`: Ürün ağırlığı (gram)
    - `product_length_cm`: Ürün uzunluğu (cm)
    - `product_height_cm`: Ürün yüksekliği (cm)
    - `product_width_cm`: Ürün genişliği (cm)

5. **olist_sellers_dataset.csv**:
    - `seller_id`: Satıcı kimliği (eşsiz)
    - `seller_zip_code_prefix`: Satıcının posta kodu
    - `seller_city`: Satıcının şehri
    - `seller_state`: Satıcının bulunduğu eyalet

6. **olist_order_payments_dataset.csv**:
    - `order_id`: Sipariş kimliği
    - `payment_sequential`: Ödeme sırası
    - `payment_type`: Ödeme türü (kredi kartı, boleto, vb.)
    - `payment_installments`: Taksit sayısı
    - `payment_value`: Ödeme miktarı

7. **olist_order_reviews_dataset.csv**:
    - `review_id`: İnceleme kimliği (eşsiz)
    - `order_id`: Sipariş kimliği
    - `review_score`: İnceleme puanı (1-5 arası)
    - `review_comment_title`: İnceleme başlığı
    - `review_comment_message`: İnceleme mesajı
    - `review_creation_date`: İncelemenin oluşturulma tarihi
    - `review_answer_timestamp`: İncelemeye cevap verme tarihi

8. **olist_geolocation_dataset.csv**:
    - `geolocation_zip_code_prefix`: Posta kodu
    - `geolocation_lat`: Enlem
    - `geolocation_lng`: Boylam
    - `geolocation_city`: Şehir
    - `geolocation_state`: Eyalet


## Sonuçlar

Bu proje sayesinde, Brezilya e-ticaret piyasası hakkında derinlemesine içgörüler elde edilmiştir. Analizler, müşteri davranışları, ürün performansı ve satıcı etkinlikleri gibi önemli konulara ışık tutmuştur. Bu içgörüler, e-ticaret işletmeleri için stratejik kararların alınmasında kullanılabilir.


