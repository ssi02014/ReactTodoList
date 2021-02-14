# 💻React TodoList App
### React(with.SCSS)로 만들어본 TodoList

<br />

### ✅ Github Page : https://ssi02014.github.io/ReactTodoList/

<br />

## 🎥 HomePage View
![13](https://user-images.githubusercontent.com/64779472/97331859-2f840980-18bd-11eb-9ef4-5d41916242ba.PNG)

## 🔖 React TodoList App을 사용하기 전 행동 수칙
1. **" npm install or yarn install "** 을 App을 Clone하신 폴더에서 입력해주세요. (프론트엔드 종속성 다운받기)
2. **" npm start or yarn start "** 를 통해 App을 실행시켜주세요.

<br />
<br />

## 👨🏻‍💻 TodoList App 기능
1. **TodoList**
    - TodoItem Insert 기능
    - TodoItem Remove 기능
    - TodoItem Toggle 기능

<br />
<br />

## 🏃 React Icon 사용 방법
```javascript
    import { MdRemoveCircleOutline } from 'react-icons/md';

    <div className="remove">
        <MdRemoveCircleOutline />
    </div>
```

<br />

## 🏃 useCallback
### useCallback: 특정 함수를 새로 만들지 않고 재사용 하고자 할때 사용
```javascript
    const onChange = useCallback(e => {
        setValue(e.target.value);
    }, []);
```

<br />
<br />