# nbackdoor
**backdoor system**

### todo
- [x] 添加 from 字段
- [x] 安全密码输入
- [x] command-line help messages：https://github.com/docopt/docopt
- [x] 下载文件
- [x] ShowDialog 执行完毕返回 result 消息
- [x] console output redirect test
- [x] transfer buf (for 'chars')
- [x] arguments splite

- [ ] 获取动态服务器 ip
- [x] esc 终止运行中的命令
- [ ] send_data 和 send_char 融合

## tofix
- [x] 执行 ShowDialog 命令，参数使用中文字符串失败
- [x] connect to client success 处理
- [ ] cat 测试


## note
[pyinstaller](https://github.com/pyinstaller/pyinstaller)

## give up
- [ ] backdoor 端使用 Windows Services 后台执行：https://github.com/Skycrab/pymgr
- [x] jobs pool：用户异步命令执行结果返回并储存在服务端
- [ ] jobs -clean
- [ ] sae branch
- [ ] 考虑 pre_send_char