![image](https://github.com/minjukimmm/react_basiccc/assets/129017089/9dda5835-f8ff-4405-8686-43b2e74ff044)

    npm i json-server
    
# db.json 파일 만들기
![image](https://github.com/minjukimmm/react_basiccc/assets/129017089/a53f89dd-9d66-4067-ba5c-49e42fa56c51)

# db.json파일은 root에 만들어야한다

 ![image](https://github.com/minjukimmm/react_basiccc/assets/129017089/e46ee969-e8ac-4e6c-98e5-1154705351b6)
 
 
# db.json 실행하기
![image](https://github.com/minjukimmm/react_basiccc/assets/129017089/00bbf195-4c08-4bff-9a46-c733e04f5e16)

# 위와 같이 실행하면 port를 3000번을 사용하기 때문에 react와 중복이 되어버린다.
# 그래서 port를 변경해 주어야 한다
    json-server --watch db.json --port 3004
