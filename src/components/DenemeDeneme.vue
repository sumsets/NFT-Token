<template>
<div id="head">
<div id="status-bar">
<div id="status-bar-left">{{time}}</div>
<div id="status-bar-right">
<div>{{mobil}}</div>
<div>{{connect}}</div>
<div>{{battery}}</div>
</div>
</div>
<div id="back-more-bar">
<div id="back-button">{{back}}</div>
<div id="more-button">{{more}}</div>
</div>
<div id="wallet-token-bar">
<div id="wallet">
<div id="wallet-icon">{{dolar}}</div>
<div id="director">{{name}}</div>
</div>
<div id="token">
<div id="token-icon">{{euro}}</div>
<div id="token-total">{{token}}</div>
</div>
</div>
</div>
</template>
<script>
export default {
  data() {
    return {
      time: '20:36',
      mobil: 'sinyal',
      connect: 'wifi',
      battery: 'full',
      back: '←',
      more: '...',
      dolar: '$',
      euro: '€',
      name: 'Metehan',
      token: '1001',
    };
  },
};
</script>

<style scoped lang="scss">
#status-bar {
display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 15px 3px;
}
#status-bar-right{
    display: flex;
    flex-wrap: wrap;
    }
#back-more-bar{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 15px 3px;
}
#wallet-token-bar{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 15px 3px;
}
#wallet{
    display: flex;
    flex-wrap: wrap;
}
#token{
    display: flex;
    flex-wrap: wrap;
}
</style>
