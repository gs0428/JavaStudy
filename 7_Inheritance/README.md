// * **연습 문제**
   
    1. Drink라는 추상클래스에서 alc() 도수를 출력하는 메소드를 선언한다. Beer, Soju, Wine은 Drink를 상속하고 각각의 도수는 다르다. Main클래스에서는 Beer, Soju, Wine의 도수를 출력한다.
    2. 오버라이딩 메소드, 다형성의 관계 살펴보기
    3. 부모 클래스를 통해 자식 클래스 생성 후 관련 프로그램 

* **도전 문제**
   
    1. Apple이라는 클래스는 Frisbee와 Astore의 부모클래스이다. Apple이라는 클래스는 아래와 같다

```java
import java.util.*;

public abstract class Apple {
	
	Random ran = new Random();                  // 난수 생성 클래스
	int money = ran.nextInt(11) + 20;           // 수리비는 20~30만원 사이 난수
	
	public void fix() {
		System.out.println("수리를 합니다.");
	}
	

}
