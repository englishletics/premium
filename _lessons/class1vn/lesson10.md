---
layout: lesson
class: "1"
lesson: "10"
lang: vn
attr:
  class: "1"
  lesson: "10"
  lang: vn
---

{%  include voice.html attr=page.attr  
	identifier="vocabulary"  init=true
	title="Lesson 1.10: Adjective + preposition"        
	translation="Tính từ + giới từ"
    tag="h1" %}

## Vocabulary   *Từ vựng*

{% include wordgrid.html lang=page.lang
		class=page.class 
		lesson=page.lesson 
		section="vocabulary"
		voiceover="vocabulary"
		database=site.data.vocabulary 
		trial=site.trialdeploy %}

{%  include voice.html attr=page.attr  
	identifier="examples1"  init=true
	title="1. Examples"        
	translation="Ví dụ"
    tag="h2" %}

1. {% include play.html identifier="examples1" start=5.1 stop=10.3 %} **I am sorry for hurting your feelings.**     
*Tôi xin lỗi vì làm tổn thương cảm giác của bạn.*      
2. {% include play.html identifier="examples1" start=10.3 stop=15.1 %} **I am used to loneliness.**     
*Tôi đã quen với sự cô đơn.*     
3. {% include play.html identifier="examples1" start=15.1 stop=21.3 %} **The accountant is not responsible for taking care of customers.**     
*Người kế toán thì không chịu trách nhiệm cho việc chăm sóc khách hàng.*     
4. {% include play.html identifier="examples1" start=21.4 stop=27.3 %} **I am tired of waiting for him.**     
*Tôi mệt mỏi vì chờ đợi anh ấy.*     
5. {% include play.html identifier="examples1" start=27.3 stop=33.3 %} **I am afraid of speaking in public.**     
*Tôi sợ phải nói trước đám đông.*    
6. {% include play.html identifier="examples1" start=33.4 stop=38.3 %} **I am discouraged by what he said.**      
*Tôi nản với những điều anh ta đã nói.*      
7. {% include play.html identifier="examples1" start=38.4 stop=43.3 %} **I am sick of doing homework every day.**      
*Tôi phát ốm vì làm bài tập về nhà hằng ngày.*      
8. {% include play.html identifier="examples1" start=43.3 stop=47.3 %} **The restaurant is full of customers.**      
*Nhà hàng thì đầy khách.*      
9. {% include play.html identifier="examples1" start=47.4 stop=55.3 %} **Claudia is known for being the most beautiful woman in town.**      
*Claudia được biết đến như là người phụ nữ đẹp nhất trong thị trấn.*      
10. {% include play.html identifier="examples1" start=55.4 stop=62.3 %} **I am quite nervous about the presentation tomorrow.**     
*Tôi khá hồi hộp về bài thuyết trình ngày mai.*     

{%  include voice.html attr=page.attr  
	identifier="examples2"  init=true
	title="2. Examples"        
	translation="Ví dụ"
    tag="h2" %}

1. {% include play.html identifier="examples2" start=5.4 stop=8.3 %} **Are you angry with me?**  
*Bạn đang giận tôi hả?*  
2. {% include play.html identifier="examples2" start=8.4 stop=14.3 %} **Is the manager responsible for contacting customers?**  
*Có phải người quản lí chịu trách nhiệm cho việc liên lạc với khách hàng?*
{% if site.trialdeploy %}
	{% include list_placeholder.html  attr=page.attr     start=3 stop=13 %}
	{% else %}
3. {% include play.html identifier="examples2" start=14.3 stop=19.3 %} **Is the student good at learning languages?**  
*Người học sinh đó có giỏi học ngôn ngữ không?*
4. {% include play.html identifier="examples2" start=19.4 stop=24.3 %} **Are you disappointed with the result of the exam?**   
*Có phải bạn thất vọng với kết quả của bài kiểm tra?*
5. {% include play.html identifier="examples2" start=25.4 stop=30.3 %} **Are you interested in becoming a singer?**    
*Bạn có hứng thú trở thành ca sĩ không?*
6. {% include play.html identifier="examples2" start=30.4 stop=37.3 %} **Is the secretary excited about the upcoming holiday?**    
*Cô thư kí có hào hứng với kì nghỉ sắp tới không?*     
7. {% include play.html identifier="examples2" start=37.4 stop=44.3 %} **Are the man and the woman satisfied with the service at the hotel?**    
*Người đàn ông và người phụ nữ đó có hài lòng với dịch vụ tại khách sạn không?*     
8. {% include play.html identifier="examples2" start=44.4 stop=50.3 %} **Are you bored with doing the same job again and again?**     
*Bạn có chán với việc làm đi làm lại cùng một công việc không?*     
9. {% include play.html identifier="examples2" start=50.4 stop=55.3 %} **Is she good at solving problems?**     
*Cô ta có giỏi giải quyết vấn đề không?*     
10. {% include play.html identifier="examples2" start=55.4 stop=61.3 %} **Are you used to the terrible traffic jam in Saigon?**     
*Bạn có quen với giao thông kinh khủng ở Sài Gòn chưa?*     
	{% endif %}