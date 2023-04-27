# Trattention-Atttention_Training

![](https://imgur.com/PtP6Lva.jpg)

## 一、前言
近年來由於兒童接收大量環境變化的刺激，以及天生遺傳、性格等原因，導致許多兒童容易受外界干擾而產生專心度不足的問題。兒童專注力不足更是二十一世紀的文明病，根據親子天下 2018 年的專注力調查顯示，超過九成的學齡教師認為兒童專注力不足。英國經過長期追蹤一萬多名兒童，發現孩子七歲時專注力的表現結果，能夠預測他們十六歲時高中的學業表現。相較於專注力運作有問題的孩子，有良好專注力的孩童，其學業成就擁有較佳的發展潛能。專注力不足不僅影響他們的學習狀況，也擴及到兒童的人際關係、心理狀態。
另外，Kenneth Rubin 提倡「內在驅動」，以玩樂的方式更能讓孩子投入專注，發展創造力、社交能力和同理心。透過遊戲方式引導，更能激發孩童的興趣，使其在心情愉悅的狀態下，同時達到培養專注力的效果。我們相信經由遊戲的方式，能夠讓孩童自主性的參與，達成良好的專注力體驗。
總結以上，本組希望可以結合智慧型裝置設計一款可以讓兒童在無壓力、健康愉快的情況下提升專注力的系統。

## 二、創意描述
本系統結合 MAD GAZE 骨傳導智慧手錶、腦波儀與平板，提供孩童訓練專注力的遊戲，並透過簡易的介面，讓孩童能夠更容易且上手的使用本系統。希望藉由多方智慧裝置的串連，運用手錶創新的遊戲體驗，輔以腦波儀測量並得到專注力數值，比對訓練前後專注力的變化。


## 三、系統功能簡介

1. 腦波檢測系統
利用閱讀短篇文章同時配戴腦波儀來監測專注力。閱讀完畢後會給予使用者簡單的題目，請使用者回答，檢測使用者是否有用心閱讀，測驗完畢後系統會將腦波儀偵測並分析而得到的專注力數值上傳至資料庫，記錄專注力數值的變化。
骨傳導手勢搭配專注力訓練
系統基於以下三個理論作為此系統訓練的基本概念
- 培爾曼式記憶訓練法：訓練記憶力的同時提高專注力。
- 舒爾特方格理論：訓練飛行員視、聽、動覺增加穩定性的方法。
- 斯特魯普測驗：使用者選擇性過濾不必要的資訊。
系統搭配 Mad Gaze Watch 骨傳導智慧手錶，提升使用者的專注力。有別於以往的傳統遊戲，本系統簡化遊戲畫面的內容，更著重在人機的互動性、手眼協調以及專注力的培養。訓練以性質的不同分類成三大項：圖形配對、舒爾特方格、記憶力翻牌，遊戲也個別設計不同難易度。
3. 使用者帳戶
使用者於初次登入前須先填寫個人相關資料，例如：姓名、性別、年齡等。建檔完成後會將此資料匯入資料庫，以便使用者查看自己的遊戲資料/專注力數值。
4. 使用者數據圖表顯示化
為方便使用者查看，此功能會將「使用者專注力測驗的腦波儀數據」、「訓練結果」、「近期訓練秒數比較」和「與其他使用者最高秒數的平均之比較」以視覺化的圖表顯示，讓使用者能快速了解自己專注力提升的程度。

## 四、系統特色
體感交互技術教育應用：
本系統以智慧裝置與創新設計為主軸，將專注力訓練遊戲與智慧裝置結合，創造出新的體感訓練模式。利用骨傳導手勢搭配平板的操作模式來訓練使用者的交替性專注力，交替性專注力為在不同的目標物之間轉移注意力來完成一件任務，以本系統為例使用者在手勢操作和完成遊戲之間轉移注意力來完成訓練。
智慧穿戴裝置精準測量應用：
本系統使用便於攜帶的智慧穿戴裝置- Neuro Sky 腦波儀，Neuro Sky 的腦電感測技術精確度高，方便攜帶且成本低，Neuro Sky 的腦電設備與研究級腦電設備相比較後顯示，其精確度可達研究級設備的 96% 以上。本系統運用 Neuro Sky 的演算法得到的 eSense 專注力指數（範圍為 0 至 100）來判斷使用者的專注力變化。
以 User-Centered Design 為宗旨：
以人為本作為設計基礎，輔以使用者測試優化系統，藉由設計簡單、友善的操作界面以及人性化操作指令來減少使用障礙，開發出一款高親善度的遊戲設計，讓訓練專注力不再是冷冰冰且帶有距離感，更能讓使用者願意透過此系統進行專注力訓練。
	
## 五、系統開發工具與技術

![](https://imgur.com/tLAQJ2p.jpg)

APP 透過 Firebase Authentication 登入驗證，讓建檔者能夠獲得權限來存取與操作系統。
APP 將資料上傳至 Firebase 儲存，資料為個人相關資料、遊戲紀錄、專注力分析紀錄。
APP 使用 Java 語法，利用 Android Studio 作為程式碼編譯器。
	
## 六、系統使用對象
我們系統的主要目標族群為 8-12 歲有專注力問題的孩童，希望這些孩童經由使用我們的系統能夠協助他們改善專注力不足的問題。

## 七、系統使用環境
我們系統的服務合作對象為教育機構、輔導中心及醫療中心，機構人員協助使用者配戴設備，輔導專注力遊戲訓練的順利進行。使用場合則以室內空間為主。使用者先配戴 NeuroSky 腦波儀，查看測驗文章同時偵測使用者的專注力數值。透過平板開啟本系統遊戲，查看訓練及專注力腦波測驗的結果。並且藉由 Mad Gaze Watch 骨傳導手錶的穿戴，以不同手勢控制遊戲的選取功能。本系統的開發環境為平板端適用 Mad Gaze Watch Android SDK 、 Android Studio。
