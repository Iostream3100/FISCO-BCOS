## build_chain.sh代码阅读分析       -Feng Yun

1. help() [Line 38]

   ​		打印出该控制台的命令列表与参数。

2. LOG_WARN() [Line 67]

   ​		报告WARNING。

3. LOG_INFO() [Line 73]

   ​		报告信息。

4. parse_params() [Line 79]

   ​		解析输入的参数。

5. print_result() [Line 118]

   ​		打印出控制台的当前信息，包括开始端口、服务器IP、状态类型、RPC收听IP、SDK PKCS12密码、输出目录、证书认证key目录、国密模式。

6. fail_message() [Line 140]

   ​		打印失败信息。

7. check_env() [Line 148]

   ​		检查环境，查看openssl是否安装并检测记录系统。

8. check_and_install_tassl() [Line 167]

   ​		检查tassl是否安装，如未安装则安装。

   ​		tassl为完全支持国密体系的openssl。

9. getname() [Line 178]

   ​		获取名称。

10. check_name() [Line 190]

    ​		检查名称是否符合。

11. file_must_exists() [Line 199]

    ​		检查文件是否存在，若不存在则输出相应信息。

12. dir_must_exists() [Line 206]

    ​		检查目录是否存在，若不存在则输出相应信息。

13. dir_must_not_exists() [Line 213]

    ​		检查目录是否不存在，若存在则输出相应信息。

14. gen_chain_cert() [Line 220]

    ​		生成链证书。

15. gen_agency_cert() [Line 234]

    ​		生成代理证书。

16. gen_cert_secp256k1() [Line 259]

    ​		获取secp256k1的证书，其中secp256k1是指比特币中使用的ECDSA（椭圆曲线数字签名算法）曲线的参数。

17. gen_node_cert() [Line 274]

    ​		生成节点的证书。其中先检验openssl版本是否支持secp256k1，若不支持则提示升级。

18. generate_gmsm2_param() [Line 303]

19. gen_chain_cert_gm() [Line 314]

20. gen_agency_cert_gm() [Line 340]

21. gen_node_cert_with_extensions_gm()  [Line 364]

22. gen_node_cert_gm() [Line 378]

23. generate_config_ini() [Line 418]

24. generate_group_genesis() [Line 498]

25. generate_group_ini() [Line 529]

26. generate_cert_conf() [Line 548]

27. generate_script_template() [Line 584]

28. generate_cert_conf_gm() [Line 595]

29. generate_node_scripts() [Line 720]

30. genTransTest() [Line 793]

31. generate_server_scripts() [Line 858]

32. parse_ip_config() [Line 888]

33. main() [Line 904]

    



