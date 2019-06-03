## build_chain.sh代码阅读分析       -Feng Yun

1. help() [Line 38]

   ​	打印出该控制台的命令列表与参数。

2. LOG_WARN() [Line 67]

   ​	报告WARNING。

3. LOG_INFO() [Line 73]

   ​	报告信息。

4. parse_params() [Line 79]

5. print_result() [Line 118]

6. fail_message() [Line 140]

7. check_env() [Line 148]

8. check_and_install_tassl() [Line 167]

9. getname() [Line 178]

10. check_name() [Line 190]

11. file_must_exists() [Line 199]

12. dir_must_exists() [Line 206]

13. dir_must_not_exists() [Line 213]

14. gen_chain_cert() [Line 220]

15. gen_agency_cert() [Line 234]

16. gen_cert_secp256k1() [Line 259]

17. gen_node_cert() [Line 274]

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

    



