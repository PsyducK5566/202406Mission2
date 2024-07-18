Message from mentor:

我是六角學院的助教 姵吟 ，

恭喜同學完成主線任務二的關卡，
整體的結構沒什麼問題～



以下有幾點可優化的地方提供給同學：

包住 logo 和 nav 的是 container-header-inner ，所以 Flex 要設定在 container-header-inner，並加上 align-items:center;




在行動版可以在 container-header-inner 設定 justify-content: space-between;，讓 logo 和漢堡選單分開




.header 建議加上 padding 和 z-index，沒有 z-index 的話，滾動畫面時，.banner 會覆蓋 .header




.footer-title img 建議加上 a 連結，增加使用者體驗


Thank U!
