Rails Routing Practice
======================

### การทดลองเพื่อสังเกตพฤติกรรมของ Ruby on Rails ในการสร้าง routes
### โดยเริ่มแรก จะใช้ resource เพื่อให้ Ruby on Rails สร้าง CRUD RESTful API ให้ ได้ผลการทดสอบดังภาพ

## GET /blogs
<img 
  src="Screenshot 2566-08-21 at 13.24.10.png"
  style="width: 75%; height: auto;">

## GET /blogs/:id
<img 
  src="Screenshot 2566-08-21 at 13.24.21.png"
  style="width: 75%; height: auto;">

## GET /blogs/:id/edit
<img 
  src="Screenshot 2566-08-21 at 13.24.30.png"
  style="width: 75%; height: auto;">

## POST /blogs
<img 
  src="Screenshot 2566-08-21 at 13.24.43.png"
  style="width: 75%; height: auto;">

## PUT /blogs/:id
<img 
  src="Screenshot 2566-08-21 at 13.24.51.png"
  style="width: 75%; height: auto;">

## DELETE /blogs/:id
<img 
  src="Screenshot 2566-08-21 at 13.24.59.png"
  style="width: 75%; height: auto;">


### แต่ในกรณีที่ต้องการสร้าง routes เอง สามารถทำได้ โดยมี format ลักษณะดังนี้
## HTML_METHOD '/routes', to: 'controller#action'

### ยกตัวอย่างเช่น

## get '/info/news' to: 'info#get_new'
<img 
  src="Screenshot 2566-08-21 at 13.25.11.png"
  style="width: 75%; height: auto;">
