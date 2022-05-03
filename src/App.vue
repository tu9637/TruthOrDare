<script setup lang="ts">
import { ref } from 'vue'
// 真心话
const Truth = ref([
  '如果拉屎时，被捅了一刀，你是先拉完，还是先追歹徒？',
  '这四个人掉水里，你先救谁？ 1.刘强东（清空购物车）2.马云（可得1000万）3.王健林（当万达董事长一年）4.马化腾（有50%几率获得10亿）',
  '如果有人吻你1.6米的地方，会吻在你哪里？',
  '如果你男票被邪恶的女巫施法变成了一只巴掌大的蟑螂，他要两年才会变回来，他还会说话，还有思想，你还会跟他在一起或养着他吗？',
  '如果第二天醒来发现你和爱豆结婚了，你会做些什么？',
  '假如让你选你现任男友和王思聪，你会选择哪个？',
  '如果你手机里的第15张照片是上辈子杀死你的东西，那么你的死因是什么？',
  '你女朋友和你最讨厌的人的灵魂互换了，要亲你最讨厌的人他们才能换回来，你亲不亲？',
  '假如让你向你最讨厌的人磕头并叫爷爷，磕一次给一万人民币，同时会朋友圈直播你磕头，你愿意吗？',
  '你最喜欢的人竟然和你最讨厌的人在一起了，你最想对他们两个说哪四个字？',
  '你情敌和曾经背叛你的人同时掉入河中，并且他们不会游泳，你是选择蹦迪还是去KTV？',
  '如果有个按钮按下去你会得到十万人民币，但你讨厌的明星会一跃成为一线巨星，你会按吗？',
  '你和对象还有其他人一起玩大冒险，如果你抽到和别人接吻的惩罚，你会照做还是拒绝？',
  '如果你变成了蚊子，如何让别人知道你是人类？',
  '在男朋友/女朋友家里，突然对方的家人回来了，你会藏在衣柜或床底吗？',
  '如果你高考即将迟到，路上遇到受重伤的老人你会救吗?',
  '自我介绍的时候你会虚报自己的身高吗？是报高还是报低？',
  '巧克力味的粑粑和粑粑味儿的巧克力，必须要吃一个，你吃哪个？',
  '如果有一天在外面你很急着上厕所，附近却找不到洗手间你会怎么办？',
  '假如你对象在危及生命的情况下，把你抛下一个人跑了，你会怎么做？',
  '你和朋友玩真心话大冒险，你抽中的题目是去厕所门口站着，对每一位从里面出来的人鼓掌并且说，您拉的真好！你硬着头皮上了，这时候厕所里出来的是你喜欢的人，你会怎么做？',
  '你爸和你妈掉水里了你救谁？',
  '如果你的朋友让你冒充TA去见TA的网恋对象，你会去吗？',
  '如果你男/女朋友和你在恋爱期间，TA还在玩各种交友软件，你会接受吗？',
  '如果对象嫌你丑，你会去整容吗？',
  '前任有新欢官宣后，半夜给你发暧昧信息你会怎么做？',
  '如果你要跟一个同性接吻，你会跟谁？',
  '如果你对象骗你说删了前任的联系方式但其实根本没有删，你会怎么样？',
  '如果你有一个分身，分身能让你永生，但一旦分身受伤则你死，你愿意吗？',
  '如果你玩的最好的异性朋友因为你有了对象把你删了你会怎么样？'
])
// 大冒险
const BudRedhead = ref([
  `模仿小猪佩奇说：“我是佩奇（猪叫），这是我的弟弟乔治，这是我的妈妈，这是我的爸爸。”`,
  `3秒内快速念出“黑化肥发灰会挥发 灰化肥挥发会发黑”`,
  `模仿绿茶的语气说一句话，例如：哥哥是在嫌妹妹胖吗？呜呜呜，妹妹会减肥的，哥哥不要这样说人家。`,
  `大声念出：“嘤嘤嘤，人家受委屈了啦，快来哄哄人家，要亲亲要抱抱要举高高。”`,
  `和你左边的人，面对面拉着双手，转圈跳，边跳边唱：“爱的魔力转圈圈”`,
  `给一位同性好友发语音消息“想要一杯芋泥啵啵奶茶，不要奶茶不要芋泥，只要啵啵”`,
  `开免提，随便拨打一个陌生人电话，无论男女都对他/她说，我爱你，然后跟对方聊天不少于30秒`,
  `在朋友圈发：今天买彩票中了1w，点赞的每人发5元红包`,
  `大喊：屎真香，屎真香，屎真香！`,
  `发消息给任意互关好友：一起拉屎吗？我出纸。`,
  `给喜欢的人发一张你觉得自己最可爱的照片。`,
  `把抖音/快手的喜欢列表截图发出来。`,
  `把袜子脱下来放到鼻子边，拍照发出来并语音说真香。`,
  `模仿洪世贤说一句：你好骚啊。`,
  `在微信搜索“性感”，读出显示出来的第一条信息。`,
  `模仿美少女战士水冰月台词大声喊出“我要代表月亮，消灭你们！”`,
  `深情的唱出“怎么也飞不出花花的世界 原来我是一只酒醉的蝴蝶”`,
  `在朋友圈/QQ空间里艾特一位异性，并说你是我的了。`,
  `把你的相册截图发出来。`,
  `给联系人里第21个打电话 说“你好，我是秦始皇，我在陕西3000吨黄金和300万秦兵被封印，现在只需要399元就能解封，只要你打钱给我，待我解封之日，我就收你当干儿子，立为太子”`
])
const showButton = ref(false)
// 定时器ID
const id = ref(-1)
const timeId = ref(-1)
// 开启定时器
const set = (length: number) => {
  timeId.value = window.setInterval(() => {
    const n = Math.floor(Math.random() * length)
    ShowContent.value = Truth.value[n]
    console.log(Math.floor(Math.random() * length))
  }, 100)
}
// 清除定时器
const clear = () => {
  let num = 0
  id.value = window.setInterval(() => {
    if (num >= 5) {
      clearInterval(timeId.value)
      clearInterval(id.value)
      showButton.value=false
    }
    num++
  }, 1000)
}
// 展示数据
const ShowContent = ref('')
const defaultShow = ref('请选择真心话还是大冒险')
// 点击真心话
const handleTruth = () => {
  showButton.value = true
  ShowContent.value = ''
  const length = Truth.value.length
  set(length)
  clear()
}
// 点击大冒险
const handleBudRedhead = () => {
  showButton.value = true
  ShowContent.value = ''
  const length = BudRedhead.value.length
  set(length)
  clear()
}
// 手动停止定时器
const handleClear = () => {
  clearInterval(timeId.value)
  clearInterval(id.value)
  showButton.value = false
}
</script>

<template>
  <template v-if="showButton">
    <div class="center"><button @click="handleClear">停止</button></div>
  </template>
  <template v-else>
    <div class="box">
      <div class="left"><button @click="handleTruth">真心话</button></div>
      <div class="right"><button @click="handleBudRedhead">大冒险</button></div>
    </div>
  </template>
  <div class="bottom">
    <p v-if="ShowContent">{{ ShowContent }}</p>
    <p v-else class="default">{{ defaultShow }}</p>
  </div>
</template>

<style lang="less" scoped>
.center {
  display: flex;
  justify-content: center;
  margin: 100px auto;
  width: 500px;
  button {
    font-size: 24px;
    padding: 5px 10px;
    border: 1px solid #000;
    border-radius: 5px;
  }
}
.box {
  display: flex;
  justify-content: space-between;
  margin: 100px auto;
  width: 500px;

  .left,
  .right {
    button {
      font-size: 24px;
      padding: 5px 10px;
      border: 1px solid #000;
      border-radius: 5px;
    }
  }
}
.bottom {
  margin: 100px auto;
  width: 700px;
  font-size: 30px;
  .default {
    text-align: center;
  }
}
</style>
