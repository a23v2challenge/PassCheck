# PASS-NICE
[NICE아이디](https://www.niceid.co.kr/index.nc/index.nc) 본인인증 요청을 자동화해주는 비공식적인 
모듈입니다.<br>

## **교육용 및 학습용으로만 사용해 주세요**<br>
이 repo를 사용함으로써 발생하는 모든 피해나 손실은 모두 본인의 책임입니다. 

또한 **[NICE아이디](https://www.niceid.co.kr/index.nc/index.nc) 및 [한국도로교통공사](https://ex.co.kr/)측의 삭제 요청이 있을 경우, 즉시 삭제됩니다.**<br>

**해당 모듈을 통한 여러 개발 & 창작물의 판매을 허용합니다.**<br>

문의 : a23v2challenge@proton.me
<br>

## 기능
- SMS 본인인증 (MVNO 포함, 모든 통신사를 지원합니다)

## Common Informations
### 기본 반환 형식:
```py
{
    "Success": Boolean,
    "Message": Message (실패시 실패메시지가 반환됩니다.)
}
```
모든 파라미터는 "string" 타입으로 처리됩니다.

### ISP(Carrier)
- SK, KT, LG
- SMVNO, KMVNO, LMVNO
