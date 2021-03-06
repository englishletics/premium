---
layout: lesson
class: "2"
lesson: "25"
lang: vn
attr:
  class: "2"
  lesson: "25"
  lang: vn
---

{%  include voice.html attr=page.attr  
	identifier="vocabulary"  init=true
	title="Lesson 2.25: Phrasal verbs"        
	translation="Cụm động từ"
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
	identifier="conversation"  init=true
	title="Conversation"        
	translation="Đối thoại"
    tag="h2" %}

> {% include play.html identifier="conversation" start=1.55 stop=4.15 %} Person 1: **Jake? What's the matter? You look upset.**    
*Jake? Có vấn đề gì vậy? Trông bạn buồn quá.*    
> {% include play.html identifier="conversation" start=4.25 stop=8.55 %} Person 2: **I broke up with Janice. I just had to, I couldnt be with her anymore.**    
*Tôi đã chia tay với Janice. Tôi phải làm vậy, tôi không thể bên cạnh cô ta nữa.*     
> {% include play.html identifier="conversation" start=8.55 stop=11.45 %} P1: **Oh. I'm sorry to hear that. I'm sure it was for the best.**     
*Ồ, tôi rất tiếc khi nghe điều đó. Tôi chắc thế này là tốt nhất.*   
> {% include play.html identifier="conversation" start=11.55 stop=15.75 %} P2: **I think so. But I feel bad because she started crying as soon as I told her.**    
*Tôi nghĩ vậy. Nhưng tôi thấy tệ vì cô ấy bắt đầu khóc ngay khi tôi nói với cô ấy.*    
> {% include play.html identifier="conversation" start=16.15 stop=17.55 %} P1: **Why did you break up with her?**   
*Tại sao bạn chia tay cô ấy vậy?*    
> {% include play.html identifier="conversation" start=17.75 stop=22.25 %} P2: **She has anger issues. I finally figured out she isn't going to change.**   
*Cô ấy có vấn đề với sự nóng giận. Tôi cuối cùng cũng hiểu được là cô ấy sẽ không thay đổi.*   
> {% include play.html identifier="conversation" start=22.35 stop=25.10 %} P1: **I see. In that case it's probably for the best.**   
*Tôi biết. Trong trường hợp đó thì như vậy là tốt nhất.*    
> {% include play.html identifier="conversation" start=25.15 stop=29.15 %} P2: **I know. I just feel bad. I feel guilty for making her cry.**    
*Tôi biết. Tôi chỉ thấy tệ. Tôi thấy mình có lỗi vì làm cho cô ấy khóc.*     
> {% include play.html identifier="conversation" start=29.25 stop=33.15 %} P1: **Don't beat yourself up about it. You need someone better to settle down with. She'll get over it.**   
*Đừng tự giận mình nữa. Bạn cần người tốt hơn để ổn định. Cô ấy sẽ vượt qua thôi.*    
> {% include play.html identifier="conversation" start=33.65 stop=38.15 %} P2: **Yeah. I'll get over it in a week or so. It takes time to move on, I guess.**    
*Ừ. Tôi sẽ vượt qua nó trong vòng một tuần hoặc hơn. Cần thời gian để tiếp tục, tôi đoán vậy.*     
> {% include play.html identifier="conversation" start=38.35 stop=42.45 %} P1: **It does. Listen, if you need someone to talk to, you can count on me.**     
*Đúng vậy. Nghe này, nếu bạn cần ai đó để nói chuyện, bạn có thể trông cậy vào tôi.*    
> {% include play.html identifier="conversation" start=42.75 stop=46.55 %} P2: **Thanks. If I end up feeling worse, I'll give you a call.**     
*Cảm ơn. Nếu cuối cùng tôi thấy tệ hơn, tôi sẽ gọi cho bạn.*   
> {% include play.html identifier="conversation" start=46.55 stop=49.95 %} P1: **Of course. Just try not to run into her anytime soon.**      
*Tất nhiên. Cố gắng đừng chạy theo cô ta sớm quá nhé.*    

{%  include voice.html attr=page.attr  
	identifier="explanation"  init=true
	title="Explanation"        
	translation="Giải thích"
    tag="h2" %}

{%  include voice.html attr=page.attr  
	identifier="explanation"  init=false start=2.25 stop=22.55
	title="1. I broke up with Janice. I couldn't be with her anymore."        
	translation=""
    tag="h3" %}
##### *Tôi đã chia tay với Janice. Tôi không thể bên cạnh cô ta nữa.*
1. **Emily and Alex broke up when she caught him breaking into her house.**   
*Emily và Alex chia tay khi cô ta bắt gặp anh ta đột nhập vào nhà của mình.*   
2. **When she left me, I felt broken. She broke my heart.**   
*Khi cô ta bỏ tôi, tôi cảm thấy tan vỡ. Cô ta làm tan nát trái tim tôi.*    
3. **Don't bring up their break-up. You know Alex is still very sensitive about it.**   
*Đừng nhắc tới việc họ chia tay. Tôi biết Alex vẫn rất nhạy cảm về việc này.*    

{% if site.trialdeploy %}
  {% include list_placeholder.html  attr=page.attr     start=3 stop=6 %}
  {% else %}

{%  include voice.html attr=page.attr  
	identifier="explanation"  init=false start=22.75 stop=46.75
	title="2. Don't beat yourself up about it. She'll get over it."        
	translation=""
    tag="h3" %}
##### *Đừng giận mình nữa. Cô ta sẽ vượt qua được điều đó thôi.*
1. **I'm so tired of hearing him cry about his ex girlfriend. Tell him to get over it!**   
*Tôi quá mệt mỏi vì phải ngh anh ta khóc lóc về bạn gái cũ. Hãy nói anh ta vượt qua chuyện đó đi.*    
2. **Once I got over my break-up, I found a new girlfriend and I'm getting along with her just fine.**   
*Khi tôi vượt qua việc chia tay của mình, tôi tìm thấy một người bạn gái mới và tôi hợp với cô ta rất nhiều.*    
3. **I don't know how I'll go on without my boyfriend. I thought we were going to settle down and start a family.**   
*Tôi không biết làm cách nào tôi có thể tiếp tục mà không có bạn trai của mình. Tôi tưởng chúng tôi sẽ kết hôn và có một gia đình.*    

{%  include voice.html attr=page.attr  
	identifier="explanation"  init=false start=46.75 stop=60.75
	title="3. If I end up feeling worse, I'll give you a call."        
	translation=""
    tag="h3" %}
##### *Nếu cuối cùng tôi vẫn cảm thấy tệ hơn, tôi sẽ gọi điện cho bạn.*
1. **If you stay in this relationship, you'll end up in a horrible marriage.**   
*Nếu bạn vẫn trong mối quan hệ này, bạn sẽ cuối cùng kết thúc trong một cuộc hôn nhân khủng khiếp.*    
2. **Most people who try drugs end up addicted to it.**    
*Hầu hết người thử thuốc phiện cuối cùng kết thúc là nghiện nó.*   
3. **You need friends you can count on if you end up in a bad situation.**   
*Bạn cần những người bạn mà bạn có thể dựa dẫm vào nếu bạn kết thúc trong một tình huống xấu.*    

{%  include voice.html attr=page.attr  
	identifier="explanation"  init=false start=61.75 stop=81.55
	title="4. I finally figured out she isn't going to change."        
	translation=""
    tag="h3" %}
##### *Tôi cuối cùng cũng hiểu được tại sao cô ta không thay đổi.*
1. **Listening to my parents helped me figure out I have a lot to learn.**   
*Nói chuyện với ba mẹ giúp tôi hiểu ra rằng tôi có nhiều thứ phải học.*   
2. **My brother helped me figure out this math assignment. I was really stuck.**   
*Anh trai giúp tôi hiểu ra bài toán này. Tôi đã bị bí.*     
3. **Anna needs to figure out what she's going to do with her life.**   
*Anna cần phải tìm ra cô ta phải làm gì với cuộc đời mình.*    

{%  include voice.html attr=page.attr  
	identifier="explanation"  init=false start=81.75 stop=107.15
	title="5. Try not to run into her anytime soon."        
	translation="Cố gắng đừng chạy theo cô ta sớm quá."
    tag="h3" %}

1. **I ran into my sister this morning. I didn't see her since April.**    
*Cô vô tình gặp chị tôi sáng nay. Tôi không gặp chị từ tháng 4.*    
2. **Guess who I ran into at the bank! My best friend from high school. We went for coffee afterwards.**   
*Đoán xem tôi đã vô tình gặp ai tại ngân hàng! Bạn thân nhất của tôi từ trung học. Sau đó chúng tôi đi cà phê.*    
3. **I'm going to the supermarket. I really hope I don't run into my math teacher like I did last week.**   
*Tôi sẽ đi siêu thị. Tôi thật sự hi vọng tôi không vô tình gặp giáo viên dạy toán như lần trước tuần vừa rồi.*    


{% endif %}

