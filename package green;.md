## sdfsdfds

**package** green;



```
**public** **class** Operation {



**public** **static** **void** main(String[] args) {

1+1 = i + i 



# 	}
```

![](package%20green;.assets/images.png)

}

```
export const logout = createAsyncThunk(

 "login/logout",

 async (_, { rejectWithValue }) => {

  try {

   // `auth.signOut` 함수를 사용하여 로그아웃합니다.

   await auth.signOut();

   console.log("로그아웃됨");

   return true;

  } catch (error) {

   // 로그아웃에 실패하면 `rejectWithValue` 함수를 사용하여 오류 메시지를 반환합니다.

   return rejectWithValue(error.message);

  }

 }

);
```

