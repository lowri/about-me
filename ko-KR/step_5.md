## ASCII art

단순한 문자열보다 훨씬 더 재밌는것을 표현 해 봐요: 바로 ASCII 아트 입니다! ASCII 아트 (*아스키*라고 발음합니다) 는 **문자열로 나타내는 그림**을 만드는 것입니다.

+ 프로그램에 그림을 추가 해 봅시다 - 강아지 그림을 말이죠!
    
    ![screenshot](images/me-dog.png)

강아지의 다리는 키보드에서 <kbd>Shift + \</kbd>를 눌러서 입력할 수 있는 파이프 캐릭터 `|`로 만들어집니다.

+ **실행**을 클릭하면, 새 코드에 버그가 있는것을 확인 할 수 있습니다.
    
    ![screenshot](images/me-dog-bug.png)
    
    이유는 당신의 문자열에 작은따옴표 `'`가 있기 때문이에요. 파이썬은 이것을 문자열의 끝이라고 생각합니다!
    
    ![screenshot](images/me-dog-quote.png)

+ 이걸 해결하기 위해서는 역슬래시 ``를 `here's`구문에 있는 작은따옴표 앞에 넣어 줍니다. 이렇게 하면 파이썬에게 작은따옴표가 문자열의 일부라고 알려 줄 수 있습니다.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ 원하는 경우에는, 한개의 작은따옴표 대신, 세개의 작은따옴표`'''`를 사용할 수 있습니다. 이렇게 하면 하나의 `print` 구문으로 여러줄의 문자열을 출력 할 수 있습니다.
    
    ![screenshot](images/me-dog-triple-quote.png)