
# Vue Shopping Cart

一個使用 Vue.js 開發的購物車網站，提供響應式商品展示、搜尋功能及購物車管理系統。

## 使用技術
|  類別   | 技術  |
|  ----  | ----  |
| 前端  | Vue 3, SCSS, CSS Animation |
| UI/UX | 響應式設計, 動畫效果 |
| 開發工具 | Vite, Git |

## 網站架構圖
```
shopping-cart/
│
├── src/
│   ├── assets/          # 靜態資源
│   ├── components/      # 組件
│   └── App.vue         # 主應用
│
└── package.json        # 專案配置
```

## 安裝說明
```bash
git clone https://github.com/Aiden911/cart.git
cd cart
npm install
npm run dev
```

## 功能說明

### 一、商品瀏覽

#### 1. 商品列表頁面
* 進入網站首頁即可瀏覽所有商品
* 商品以網格方式展示，包含：
   * 商品圖片
   * 商品名稱
   * 價格
   * 商品狀態標籤

#### 2. 搜尋商品
* 點擊頂部搜尋框
* 輸入關鍵字（可搜尋商品名稱、描述）
* 系統即時顯示符合條件的商品

#### 3. 商品詳細資訊
* 將滑鼠移至商品卡片上方
* 顯示詳細資訊，包含：
   * 商品完整名稱
   * 詳細描述
   * 加入購物車按鈕

### 二、購物車操作

#### 1. 加入購物車
* 在商品卡片上方懸停
* 點擊「加入購物車」按鈕
* 系統顯示成功提示
* 購物車圖標更新數量

#### 2. 查看購物車
* 點擊右上角購物車圖標
* 彈出購物車視窗，顯示：
   * 已選商品列表
   * 每項商品數量
   * 小計金額
   * 總計金額

#### 3. 購物車管理
* 調整商品數量
   * 點擊 +/- 按鈕調整數量
   * 系統自動更新總金額
* 移除商品
   * 點擊商品旁的 × 按鈕
   * 商品立即從購物車移除
   * 系統自動更新總金額

### 三、檢視訂單

#### 1. 訂單確認
* 在購物車中檢視：
   * 商品項目
   * 商品數量
   * 商品單價
   * 訂單總額

#### 2. 訂單提交
* 確認購物車內容無誤
* 點擊「訂單結帳」按鈕
* 系統顯示訂單完成提示

## 操作注意事項

### 1. 操作建議
* 商品數量變更會即時更新金額
* 移除商品前建議再次確認
* 請在瀏覽器支援下使用

### 2. 使用限制
* 商品補貨中無法購買
* 購物車商品數量上限為 99
* 請在網路穩定時進行結帳

## 開發團隊
前端開發：Aiden
- GitHub: [@your-username](https://github.com/Aiden911)
- Email:forest1991911@gmail.com

## 版本資訊
* v1.0.0 (2024-10-27)
  - 完成基礎購物車功能
  - 實現商品搜尋功能
  - 新增商品動畫效果



