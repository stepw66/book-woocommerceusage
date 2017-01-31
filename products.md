# แท็บ Products

สำหรับการตั้งค่าในแท็บ Products นั้น ค่าต่างๆจะเกี่ยวข้องกับสินค้าโดยเฉพาะ ซึ่งภายใต้แท็บ Products นี้ยังประกอบไปด้วยแท็บย่อยๆอีก 4 แท็บ

1. **General** - กำหนดค่าทั่วๆไปเกี่ยวกับสินค้า
2. **Display** - กำหนดค่าการแสดงผลของสินค้า
3. **Inventory** - กำหนดค่าเกี่ยวกับคลังสินค้า หรือ สต้อกสินค้า
4. **Downloadable Products** - กำหนดค่าเกี่ยวกับสินค้าที่สามารถดาวน์โหลดได้ คือพวกสินค้าดิจิตอล นั่นเอง

![](/assets/2017-01-30_16-31-06.jpg)

---

### General

เป็นการกำหนดค่าทั่วๆไปของสินค้า เช่น หน่วยวัด เป็นต้น

![](/assets/2017-01-30_16-31-06.jpg)

-**Weight Unit** ตัวเลือกนี้ใช้สำหรับกำหนดหน่วยน้ำหนักของสินค้า ซึ่งมีค่าที่สามาถกำหนดได้ 4 ค่า

1. **kg **- กิโลกรัม
2. **g** - กรัม
3. **lbs** - มิลลิลิตร
4. **oz** - ออนซ์

-**Dimensions Unit** ตัวเลือกนี้ใช้สำหรับกำหนดหน่วยขนาดของสินค้า ซึ่งมีค่าที่สามารถกำหนดได้ 6 ค่า

1. **m** - เมตร
2. **cm** - เซ็นติเมตร
3. **mm** - มิลลิเมตร
4. **in** - นิ้ว
5. **yd** - หลา

#### Reviews

ตัวเลือกกลุ่มนี้จะเป็นตัวเลือกสำหรับการแสดงรีวิวสินค้า การรีวิวคืออะไร ก็คือที่ๆเราอนุญาติให้ผู้ซื้อสินค้ามาคอมเม้นท์และให้ดาวสินค้านั้นๆ

-**Enable ratings on reviews** อนุญาติให้ลูกค้าสามารถให้ดาวสินค้าได้

-**Ratings are required to leave a review** ลูกค้าต้องรีวิวสินค้าก่อนจึงจะสามารถให้ดาวได้

-**Show "verified owner" label for customer reviews** แสดง "ลูกค้ายืนยันตัวตนแล้ว" เหนือรีวิวของลูกค้าคนนั้นๆ

-**Only allow reviews from "verified owners"** อนุญาติเฉพาะ ลูกค้ายืนยันตัวตนแล้ว เท่านั้นรีวิวสินค้าได้

---

### Display

เป็นการกำหนดค่าการแสดงสินค้า

![](/assets/2017-01-30_16-31-25.jpg)

-**Shop Page** กำหนดหน้าสำหรับแสดงสินค้า คำแนะนำที่ผมมีให้คือ อย่าเปลี่ยนแปลงค่าใดๆ ตัวเลือกนี้สำหรับผู้ใช้ระดับสูง

-**Shop Page Display** กำหนดว่าจะให้หน้าแสดงสินค้าหน้าแรกนั้น แสดงอะไร ซึ่งมีตัวเลือกอยู่ 3 ตัวเลือก

1. **Show Products** แสดงรายการสินค้า
2. **Show Categories** แสดงหมวดหมู่สินค้า \(ต้องคลิกหมวดหมู่นี้ก่อนจึงจะเข้าไปยังหน้าแสดงรายการสินค้า\)
3. **Show Categories**  **& Products  **แสดงสินค้าและหมวดหมู่สินค้า

-**Default Category Display** กำหนดจะให้แสดงอะไรในหน้าหมวดหมู่ หน้าหมวดหมู่นั้นจะเข้าถึงได้ผ่านการคลิกที่หมวดหมู่ที่หน้าเว็บ ซึ่งมีตัวเลือกอยู่ 3 ตัวเลือก

1. **Show Products** แสดงสินค้าในหมวดหมู่นั้นๆ
2. **Show Subcategories** แสดงหมวดหมู่ย่อย ต้องคลิกหมวดหมู่ย่อยก่อนจึงเข้าไปยังหน้าแสดงรายการสินค้า
3. **Show Subcategories & Products** แสดงหมวดหมู่ย่อยและสินค้า

-**Default Product Sorting** กำหนดลำดับการจัดเรียงแสดงสินค้า มีตัวเลือกทั้งหมด 6 ตัวเลือก

1. **Default Sorting \(Custom ordering + name\)** จัดเรียงตามชื่อสินค้า
2. **Popularity \(sales\)** จัดเรียงตามความนิยม จำนวนการขาย
3. **Average Rating** เรียงตามค่าเฉลี่ยเรตติ้ง \(เรตติ้งนั้น กำหนดโดยลูกค้าที่มารีวิวสินค้า\)
4. **Sort by Most Recent** เรียงตามสินค้าใหม่สุด
5. **Sort by Price \(asc\) **เรียงตามราคาน้อยไปหามาก
6. **Sort by Price \(desc\) **เรียงตามราคามากไปหาน้อย

-**Add to cart behaviour** เป็นการกำหนดการทำงานของปุ่ม หยิบใส่ตะกร้า

1. **Redirect to the cart page after successful addition **ติ๊กเครื่องหมายถูก กำหนดให้เปลี่ยนไปหน้าตะกร้าสินค้า หลังจากหยิบสินค้าใส่ตะกร้าสินค้าเสร็จแล้ว

2. **Enable AJAX add to cart buttons on archives** ติ๊กเครื่องหมายถูก กำหนดให้อยู่หน้าเดิม โดยแสดงข้อความ หยิบใส่ตะกร้าสินค้าเรียบร้อยแล้ว ขึ้นมาให้ลูกค้าเห็นเท่านั้น

#### Product Images

ในกลุ่มนี้จะเป็นการกำหนดค่ารูปภาพสินค้า ทั้งหมดขนาดเล็กและภาพขนาดใหญ่ ซึ่งโดยปกติแล้วเรามักไม่เปลี่ยนแปลงค่าใดๆมัน ปล่อยไว้ตามเดิมที่กำหนดมาเป็นค่าแรกเริ่ม แต่อย่างไร เราลองดูว่าแต่ละตัวนั้นใช้กำหนดอะไร เพื่อเป็นการประดับความรู้

* **Catalog Images **กำหนดขนาดกว้างxยาวรูปภาพที่จะนำไปทำเป็นแคทตาลอก

-**Single Product Image **กำหนดขนาดกว้างxยาวรูปภาพที่แสดงในหน้ารายละเอียดสินค้า

-**Product Thumbnails **กำหนดขนาดกว้างxยาวรูปภาพหน้าชื่อสินค้า ภาพนี้จะแสดงในหน้ารวมสินค้า

-**Product Image Gallery **กำหนดขนาดกว้างxยาวรูปภาพที่จะนำไปทำชุดรูปภาพสินค้า

ส่วนตัวเลือก  Hard Crop? นั้นหมายถึงหลังจากย่อภาพตามขนาดต้องการแล้ว มีส่วนเหลือของภาพให้ตัดทิ้งเลยหรือไม่?

ตัวเลือก

-**Enable Lightbox for product images** ติ๊กเลือกเพื่อเปิดการใช้งาน แสดงรูปภาพด้วยเอฟเฟ็ก Lightbox \(ซึ่งเป็นการแสดงผลที่สวยงาม\) ใช้งานกับแกลเลอรี่รูปภาพสินค้าเท่านั้น

---

## Inventory

แท็บ Inventory นี้ไว้สำหรับตั้งค่า stock โดยเฉพาะ

![](/assets/2017-01-30_16-31-37.jpg)

-**Enable stock management **ติ๊กเครื่องหมายถูกถ้าหากต้องการให้ระบบช่วยดูแลเรื่องสต้อก ถ้าหากไม่ติ๊กเครื่องหมายถูก ตัวเลือกด้านล่างถัดลงไปจะไม่เกิดผลใดๆ ไม่ว่าจะตั้งค่าไว้อย่างไร เพราะฉะนั้นตัวเลือกนี้ถือว่าเป็นตัวเลือกที่จะต้องติีกเครื่องหมายถูก ถ้าหากจะให้ฟีเจอร์เรื่องสต้อกทำงาน

-**Hold Stock \(minutes\) **ระบุจำนวนนาทีที่ให้ระบบกันสินค้าไว้ให้กับออเดอร์รอจ่ายเงิน หมายถึงเมื่อลูกค้าซื้อสินค้าเสร็จแล้ว ระบบจะกันสินค้าไว้ให้ลูกค้าคนนั้น จนกว่าจะเลยเวลาตามที่กำหนดไว้ที่นี่ ในกรณีใส่เลข 0 หมายถึงไม่ต้องกันสินค้า ใครจ่ายเงินก่อนได้ไปก่อน \(สินค้าไม่พอขาย เจ้าของร้านก็เจรจากับลูกค้าเอาเองว่าจะคืนเงินหรือทำอย่างอื่น\)

-**Enable low stock notifications** ติ๊กเครื่องหมายถูกจะเป็นการบอกให้ระบบช่วยเตือนเมื่อสินค้าอยู่ในระดับต่ำ \(ด้านล่างมีให้ระบุจำนวน\)

-**Enable out of stock notifications** ติ๊กเครื่องถูกจะเป็นการบอกให้ระบบช่วยเตือนเมื่อสินค้าหมด \(ด้านล่างมีให้ระบุจำนวน\)

-**Notification Recipient\(s\)** ระบุอีเมล์สำหรับแจ้งเตือนสต้อกสินค้า กรณีต้องการระบุหลายอีเมล์ให้คั่นแต่ละอีเมล์ด้วยเครื่องหมายคอมม่า \(,\)

-**Low Stock Threshold** ระบุตัวเลขสต้อกสินค้ามีน้อย คือเมื่อสินค้าลดลงมาจนถึงตัวเลขนี้ ระบบจะมองว่าสินค้านั้นมีจำนวนน้อยแล้ว ถึงเวลาต้องเตือนแล้ว

-**Out Of Stock Threshold** ระบุตัวเลขสต้อกสินค้าหมด คือเมื่อสินค้าลดลงมาจนถึงตัวเลขนี้ ระบบจะมองว่าสินค้านั้นหมดแล้ว ถึงเวลาต้องเตือนแล้วและสินค้าชิ้นนั้นลูกค้าจะไม่สามารถซื้อได้ ท่านอาจจะระบุตัวเลขมากกว่า 0 ก็ได้ เพื่อเป็นการกันสต้อก

* Hide out of stock items from the catalog ติ๊กเครื่องหมายถูก หากไม่ต้องการซ่อนสินค้าในกรณีสินค้านั้นหมดสต้อก

* Stock Display Format เป็นการเลือกการแสดงผลตัวเลขสต้อกที่หน้าขายสินค้า ซึ่งมี 3 ตัวเลือก

* Always show stock e.g. "12 in stock" แสดงจำนวนสินค้าในสต้อกเสมอ

* Only show stock when low e.g. "Only 2 left in stock" or "In stock" แสดงจำนวนสินค้าเมื่อมีสินค้าในสต้อกน้อย นอกจากนั้นให้แสดงแค่คำว่า "In stock"

* Never show stock amount ไม่แสดงจำนวนสินค้าที่หน้าเว็บ

---

### Downloadable Products




