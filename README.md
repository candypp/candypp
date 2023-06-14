- 👋 Hi, I’m @candypp
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
candypp/candypp is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
// 获取CEX和DEX的价格
const cexPrice = 1000; // 假设CEX价格为1000
const dexPrice = 950; // 假设DEX价格为950

// 计算价格差
const priceDiff = cexPrice - dexPrice;

// 判断价格差是否大于一定值
if (priceDiff > 50) {
  console.log(`CEX和DEX的价格差大于50，当前差值为${priceDiff}`);
} else {
  console.log(`CEX和DEX的价格差小于等于50，当前差值为${priceDiff}`);
}
