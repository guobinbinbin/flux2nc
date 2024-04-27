# flux2nc
convert VIC 4.x fluxes files to NetCDF4

基于servir-vic-training项目中的flux2nc工具改进而来
修改如下
1. 选项将作为方法的参数输入
2. 修复了读取fluxes和snows文件在同一目录时的读取错误问题
3. 修复了fluxes读取串行的问题
4. 新增了批处理功能
