# vue-countime
vue 倒计时组件

# update 2018-05-11 
# CountDownTimer 倒计时组件

<!-- 调用 -->
<CountDownTimer 
    :s-time="sTime" 
    :e-time="eTime"
    v-if="beginTime"
    :callback="callback"></CountDownTimer>

