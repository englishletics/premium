---
layout: lesson
lang: pt
class: "1"
lesson: "07"
attr:
  class: "1"
  lesson: "07"
  lang: pt
---

{%  include voice.html attr=page.attr                     tag="h1"
	identifier="Vocabulary"  init=true
	title="Lesson 1.7: Adjective"        
	translation="Adjetivo"
%}

## Vocabulary   *Vocabulário*


{% include wordgrid.html lang=page.lang
		class=page.class 
		lesson=page.lesson 
		section="vocabulary"
		voiceover="Vocabulary"
		database=site.data.vocabulary 
		trial=site.trialdeploy %}


{%  include voice.html attr=page.attr                     tag="h2"
	identifier="Conversation"  init=true
	title="1. Yes / No questions"
	translation="perguntas Sim / Não"
%}


1. {% include play.html identifier="Conversation" start=4 stop=7.5 %} 1**Are your hands clean?**   
*Suas mãos estão limpas?*       
{% include play.html identifier="Conversation" start=7.1 stop=9 %} **Yes, they are clean.**    
*Sim, estão limpas.*   

2. {% include play.html identifier="Conversation" start=9 stop=12.6 %} **Is Jane a manager?**   
*Jane é gerente?*   
{% include play.html identifier="Conversation" start=12.6 stop=16.3 %} **No, she is not a manager. She is a secretary.**  
*Não, ela não é gerente. Ela é secretária.*   

{% if site.trialdeploy %}
	{% include explanation_placeholder.html  attr=page.attr     start=3 stop=11 %}
	{% else %}

3. {% include play.html identifier="Conversation" start=16.6 stop=20.2 %} **Are the students in the classroom?**    
*Os alunos estão na sala de aula?*    
{% include play.html identifier="Conversation" start=20.2 stop=23 %} **Yes, the students are in the classroom.**  
*Sim, os alunos estão na sala de aula.*   

4. {% include play.html identifier="Conversation" start=23 stop=26 %} **Is it a good book?**   
*É um bom livro?*      
{% include play.html identifier="Conversation" start=26 stop=29.5 %} **No, it's not a good book. It's pretty boring.**      
*Não, não é um bom livro. É muito chato.*    

5. {% include play.html identifier="Conversation" start=29.5 stop=33 %} **Is the weather hot outside?**   
*O tempo está quente lá fora?*     
{% include play.html identifier="Conversation" start=33 stop=36 %} **Yes, it's quite hot outside.**    
*Sim, está muito quente lá fora.*   

6. {% include play.html identifier="Conversation" start=36 stop=39.8 %} **Is he an important person in the company?**     
*Ele é uma pessoa importante na empresa?*    
{% include play.html identifier="Conversation" start=39.8 stop=44 %} **Yes, he is an extremely important person in the company.**    
*Sim, ele é uma pessoa extremamente importante na empresa.*    

7. {% include play.html identifier="Conversation" start=44 stop=47.1 %} **Is it an expensive cellphone?**    
*É um celular caro?*    
{% include play.html identifier="Conversation" start=47.1 stop=50 %} **Yes, it's a very expensive cellphone.**   
*Sim, é um celular muito caro.*   

8. {% include play.html identifier="Conversation" start=50 stop=53.6 %} **Is it an interesting movie?**     
*É um filme interessante?*    
{% include play.html identifier="Conversation" start=53.6 stop=57.7 %} **No, it's not an interesting movie. It's quite boring.**    
*Não, não é um filme interessante. É muito chato.*    
  
9. {% include play.html identifier="Conversation" start=57.7 stop=60.7 %} **Is the story interesting?**   
*A história é interessante?*    
{% include play.html identifier="Conversation" start=60.7 stop=63 %} **Yes, it's an interesting story.**    
*Sim, é uma história interessante.*    
  
10. {% include play.html identifier="Conversation" start=63 stop=66.7 %} **Is he a patient teacher?**   
*Ele é um mestre paciente?*   
{% include play.html identifier="Conversation" start=66.7 stop=70.7 %} **Yes, he is extremely patient with his students.**    
*Sim, ele é extremamente paciente com seus alunos.*    
  
11. {% include play.html identifier="Conversation" start=70.7 stop=74.4 %} **Is your manager from Germany?**    
*O seu gerente é da Alemanha?*    
{% include play.html identifier="Conversation" start=74.4 stop=77.6 %} **Yes, he is from Germany.**   
*Sim, ele é da Alemanha.*   


{% endif %}