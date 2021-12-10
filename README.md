pandas technic
1. convert 1 min ohlc into 1 day  using pandas resample()

[ resample() 메소드의 시간 단위 구간 설정 ]
- 5분 단위 구간     : resample('5T')
- 10분 단위 구간    : resample('10T')
- 20분 단위 구간    : resample('20T')
- 1시간 단위 구간   : resample('1H')
- 1일 단위 구간     : resample('1D')
- 1주일 단위 구각   : resample('1W')
- 1달 단위 구간     : resample('1M')
- 1년 단위 구간     : resample('1Y')




2. pandas 범위 행 삭제 
   
   iris2 = iris.drop(labels=range(40, 45), axis=0)




