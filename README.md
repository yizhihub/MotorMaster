##********热烈欢迎单电机FreeMaster FOC调试界面日志正式建立********2019年8月5日

###ESC-FOC_V3.0_AEE_0723a.pmp  

start: 单个电机调试。 

end  ：1. 由于引入了根据扇区切换采样，示波器界面变量命名M1_AdcIa 改为 GulDataAdc0[0]。 
       2. 增加示波器StartupTransition，用于观看切闭环瞬间波形情况。 
       3. 母线电压显示变量FLyVoltage加入自带150ms的滤波显示。
       
20190819 : 增加M1_SpeedSet变量，用于表示设定速度速度，单位为 RPM。原变量 GlUqSet设定速度范围Q值（0-1）。
