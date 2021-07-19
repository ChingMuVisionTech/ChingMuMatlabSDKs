# ChingMuMatlabSDKs
ChingMu Vrpn for matlab  
操作说明：  
1.在Matlab中执行：mex -setup， 安装VS2010编译器  
2.在Malab中执行：loadlibrary('CMVrpn','CMVrpn.h')，加载CMVrpn dll  
3.修改VRPN Server地址、BodyID  
4.调用Dll导出的函数获取刚体6DOF calllib('CMVrpn', 'CMTrackerExternTC', VrpnServer, BodyID, 0, ppos, ppos+3)  
5.调用unloadlibrary卸载dll  
