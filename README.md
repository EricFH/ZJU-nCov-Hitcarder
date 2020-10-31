# ZJU-nCov-Hitcarder

浙大nCov肺炎健康打卡定时自动脚本 

forked from [Tishacy/ZJU-nCov-Hitcarder](https://github.com/Tishacy/ZJU-nCov-Hitcarder)

# Sample .yml

```yml
- name: Working
   uses: Long0x0/zju-ncov-hitcarder-action@0.0.1
      with:
         # zju account username(student  id).
         username: ${{ secrets.ZJU_USERNAME }}
         # zju account password.
         password: ${{ secrets.ZJU_PASSWORD }}
         # (optional) dingtalk_token.
         dingtalk_token: ${{ secrets.DINGTALK_TOKEN }}
         # (optional) serverchan_key.
         serverchan_key: ${{ secrets.SERVERCHAN_KEY }}
         # (optional) pushplus_token.
         pushplus_token: ${{ secrets.PUSHPLUS_TOKEN }}
```

# Sample Repository

https://github.com/Long0x0/ZJU-nCov-Hitcarder-Sample
