# Unity_Game_About
Unity遊戲相關

包含了遊戲檔以及原始檔案

//2021/05/25

手機app的project，在library內缺少il2cpp_android的資料


//2021/10/02

遊戲玩法說明:

#無限繼承:

    無限關卡數，每回合後可以選擇一個buff
    滑鼠左鍵攻擊，左鍵快速移動，s鍵存檔，p鍵暫停，上下左右移動
    暫停介面中，可查看目前數值(pause字樣高度，向左延伸到螢幕邊界，可以找到一個按鈕，能啟動射擊模式)
     
#小狐狸:

    左右移動，上跳躍，下蹲下
  
#激光與子彈:

    無限關卡數
    鼠標瞄準敵人可獲得敵人訊息
    e,r,t,y,g,h切換武器，左鍵射擊，右鍵近戰攻擊，擊殺敵人可獲得子彈以及經驗值(升級獲得天賦點，可再天賦頁面強化)
    p鍵暫停，可切換至不同介面
    bug:怪物出生位置卡牆問題、傳送武器可傳送到牆外或牆內的問題
    
        {
            追蹤彈:追蹤攻擊，消耗能量(隨時間回復)，一定時間內連續攻擊，強化傷害以及單次發射子彈數量
            傳送:在鼠標位置定下座標，一定時間後，傳送到座標處
            狙擊槍:高傷害、射速慢
            機槍:低傷害，高射速
            步槍:普通射速、傷害
            散彈槍:單次發射子彈數增加
            揮刀:近戰攻擊
        }
