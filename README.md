# jsp_17 : jquery 이용 - 1 (Atom에서만 됬음)

![image](https://user-images.githubusercontent.com/37132897/158180068-50e84494-5e16-44df-8724-613e6adfe403.png)
- 버튼 누르기 전

![image](https://user-images.githubusercontent.com/37132897/158180114-6033615b-12d1-4ab3-8cc5-3edff9f01d0e.png)
- 버튼 누른 후

jQuery는

1. 엘리먼트를 선택할 수 있는 강력한 방법

2. 선택된 엘리먼트를 효율적으로 제어할 수 있는 방법

구글에서 jquery cdn 쳐서, uncompressed 내용(아래 script 내용) 복사 후, 붙여넣으면, jQuery 사용 가능 하다.


            function f() { // 버튼 눌렀을 때 실행되는

            $('#one').html('반갑습니다~!!!!') // 1. jquery 사용 1, #은 id를 의미

            document.getElementById('one').style.backgroundColor = 'red'; // 배경색이 빨강색이 된다.

            }

            // $('#two').click(

            //   function f(){

            //     $('p').html('반갑습니다~!!!!') // 2. jquery 사용 2

            //   }

            // );
  

