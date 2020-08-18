## Service

API Request 할 때 사용



## 사용하기

```
import requestModel from "@data/requestModel";

const fetch = async () => {
    try {
      const result = await requestModel.getMyRequestList(pagination);
      // 성공시 처리할 코드
      console.log("result", result);
      
    } catch (error) {
      // 에러 발생시 처리할 코드
      console.log(error);
    }
};
```


