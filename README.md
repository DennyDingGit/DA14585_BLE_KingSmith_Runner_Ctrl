# DA14585_BLE_KingSmith_Runner_Ctrl
使用Rensasa DA14585 SOC做的（盒馬 2.13" 墨水屏）EPD 電子價簽改成的KingSmith 跑步機遙控器
有關EPD 的硬體
  DA14585  是BLE 的SOC，可以做到BLE5.0. 有SUOTA（Software Update Over The Air）
  雖然DA14585 是有ROM的，可是這個EPD 是有燒Second boot , 可以改成外部SPI Flash Boot.
  所以可以重寫Prog 改成自用。
