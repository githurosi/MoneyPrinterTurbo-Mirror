## 📅 更新日志
### 1.0.4
#### V1.0.4
 - 添加了从静态IPv4地址启动的添加支持
 - 在OpenNetworkboot中添加了静态IPv4配置选项
 - 从OpenNetworkBoot参数中删除` - ` - `如果使用此驱动程序，请修改驱动程序参数）
 - 更新了`unload`选项以违反加载的顺序卸载驱动程序
 - 修复了未支撑的CPU上的MSR_IA32_TSC_ADJUST`访问（例如Virtualization.Framework），Thx @t0rr3sp3dr0
 - 降级的警告日志级别降至audiodxe中的info for infor（在使用此驱动程序时需要恢复在需要中包含debug_warn的能力）
 - 添加了`clearTaskSwitchbit`BOODER QUIRK以修复32位版本的MACOS在Hyper-V Gen2 VMS上的崩溃
 - 修复了旧版本的macos 10.4的providecurrentcpuinfo`和cpuid修补
 - 从ssdt-hv-dev.dsl`删除ACPI0007对象
 - 删除了不再需要的SSDT-HV-DEV-WS2022.DSL`
 - 在``sysreport''中添加了pci类名称
#### 

#### 

### 最新版资产
 - OpenCore-1.0.4-DEBUG.zip
 - OpenCore-1.0.4-RELEASE.zip

### 更新日志
#### 

