# Vue.js-Django

> Vue.js & Django 를 사용하여 Todo 앱 만들기 

https://www.inflearn.com/course/vue-js-2/

1. todo-html
• html 파일에 vue.js 코드를 작성하는 방식
• 프로그램 종료시, todo 데이터가 사라지는 단점
• 브라우저 Storage 를 사용하면, todo 데이터가 유지되지만,
• 내 노트북에서만 보이고, 다른 노트북에서는 볼 수 없음
2. todo-vue-only
• 장고에 (1.번)의 html 파일을 그대로 수용하는 방식
• 테이블을 사용하지 않아, todo 데이터 관련 단점은 (1.번)과 동일함
3. todo-django-only
• Vue.js 코드 없이, 장고 코드 만으로 todo 앱을 개발하는 방식
• 테이블을 사용하므로, 다른 사람과 데이터 공유가 가능함
• 간단하고 쉬운, 클래스형 뷰를 사용함
