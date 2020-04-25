[SERVER]

[SOURCE]
DivineEngine, filter, https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/Pro.conf, true
DivineEngine, blacklist, https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/Rejection.conf, true

[BACKUP-SERVER]

[SUSPEND-SSID]

[POLICY]

[DNS]

[REWRITE]

[URL-REJECTION]

[TCP]
# Unbreak
# > General
USER-AGENT,coffeecorp*,DIRECT
USER-AGENT,restaurant-mobile*,DIRECT
DOMAIN,app.adjust.com,DIRECT
# > Google
DOMAIN-SUFFIX,googletraveladservices.com,DIRECT
DOMAIN,analyticsinsights-pa.googleapis.com,PROXY
DOMAIN,analyticsreporting.googleapis.com,PROXY
DOMAIN,dl.google.com,DIRECT
DOMAIN,mtalk.google.com,DIRECT
# > Tencent
DOMAIN,livew.l.qq.com,DIRECT
DOMAIN,vd.l.qq.com,DIRECT
# > Strava
DOMAIN,analytics.strava.com,DIRECT

# Advertising 去广告（以及隐私追踪保护）
# > General
DOMAIN-KEYWORD,adservice,REJECT
DOMAIN-KEYWORD,analytics,REJECT
DOMAIN-KEYWORD,analysis,REJECT

DOMAIN-SUFFIX,42trck.com,REJECT
DOMAIN-SUFFIX,51.la,REJECT
DOMAIN-SUFFIX,adcolony.com,REJECT
DOMAIN-SUFFIX,adinfuse.com,REJECT
DOMAIN-SUFFIX,adjust.com,REJECT
DOMAIN-SUFFIX,adjust.io,REJECT
DOMAIN-SUFFIX,admaster.com.cn,REJECT
DOMAIN-SUFFIX,admob.com,REJECT
DOMAIN-SUFFIX,adnxs.com,REJECT
DOMAIN-SUFFIX,adnyg.com,REJECT
DOMAIN-SUFFIX,adsensor.org,REJECT
DOMAIN-SUFFIX,adsymptotic.com,REJECT
DOMAIN-SUFFIX,adtarget.tech,REJECT
DOMAIN-SUFFIX,adthor.com,REJECT
DOMAIN-SUFFIX,adwhirl.com,REJECT
DOMAIN-SUFFIX,amazon-adsystem.com,REJECT
DOMAIN-SUFFIX,amobee.com,REJECT
DOMAIN-SUFFIX,analysys.cn,REJECT
DOMAIN-SUFFIX,app-adforce.jp,REJECT
DOMAIN-SUFFIX,appads.com,REJECT
DOMAIN-SUFFIX,appcpi.net,REJECT
DOMAIN-SUFFIX,appier.net,REJECT
DOMAIN-SUFFIX,applift.com,REJECT
DOMAIN-SUFFIX,applovin.com,REJECT
DOMAIN-SUFFIX,applvn.com,REJECT
DOMAIN-SUFFIX,appsflyer.com,REJECT
DOMAIN-SUFFIX,apsalar.com,REJECT
DOMAIN-SUFFIX,apxadtracking.net,REJECT
DOMAIN-SUFFIX,axonix.com,REJECT
DOMAIN-SUFFIX,bayimob.com,REJECT
DOMAIN-SUFFIX,bjvvqu.cn,REJECT
DOMAIN-SUFFIX,bulldogcpi.com,REJECT
DOMAIN-SUFFIX,clotfun.mobi,REJECT
DOMAIN-SUFFIX,clotfun.online,REJECT
DOMAIN-SUFFIX,cloudmobi.net,REJECT
DOMAIN-SUFFIX,cnzz.com,REJECT
DOMAIN-SUFFIX,ctrmi.com,REJECT
DOMAIN-SUFFIX,exosrv.com,REJECT
DOMAIN-SUFFIX,flurry.com,REJECT
DOMAIN-SUFFIX,go2cloud.org,REJECT
DOMAIN-SUFFIX,growingio.com,REJECT
DOMAIN-SUFFIX,haloapps.com,REJECT
DOMAIN-SUFFIX,hypers.com,REJECT
DOMAIN-SUFFIX,idealads.net,REJECT
DOMAIN-SUFFIX,inmobi.cn,REJECT
DOMAIN-SUFFIX,inmobi.com,REJECT
DOMAIN-SUFFIX,inmobi.net,REJECT
DOMAIN-SUFFIX,inmobicdn.cn,REJECT
DOMAIN-SUFFIX,inmobicdn.net,REJECT
DOMAIN-SUFFIX,inner-active.mobi,REJECT
DOMAIN-SUFFIX,insurads.com,REJECT
DOMAIN-SUFFIX,ironsrc.com,REJECT
DOMAIN-SUFFIX,irs01.com,REJECT
DOMAIN-SUFFIX,iskyworker.com,REJECT
DOMAIN-SUFFIX,juicyads.com,REJECT
DOMAIN-SUFFIX,kochava.com,REJECT
DOMAIN-SUFFIX,leadboltmobile.net,REJECT
DOMAIN-SUFFIX,lenzmx.com,REJECT
DOMAIN-SUFFIX,liveadvert.com,REJECT
DOMAIN-SUFFIX,lnk0.com,REJECT
DOMAIN-SUFFIX,lnk8.cn,REJECT
DOMAIN-SUFFIX,localytics.com,REJECT
DOMAIN-SUFFIX,mdfull.com,REJECT
DOMAIN-SUFFIX,measurementapi.com,REJECT
DOMAIN-SUFFIX,medialytics.com,REJECT
DOMAIN-SUFFIX,meetrics.com,REJECT
DOMAIN-SUFFIX,meetrics.net,REJECT
DOMAIN-SUFFIX,miaozhen.com,REJECT
DOMAIN-SUFFIX,mmstat.com,REJECT
DOMAIN-SUFFIX,moatads.com,REJECT
DOMAIN-SUFFIX,mobclix.com,REJECT
DOMAIN-SUFFIX,mopub.com,REJECT
DOMAIN-SUFFIX,okjhb.xyz,REJECT
DOMAIN-SUFFIX,openx.net,REJECT
DOMAIN-SUFFIX,pubmatic.com,REJECT
DOMAIN-SUFFIX,qchannel01.cn,REJECT
DOMAIN-SUFFIX,rayjump.com,REJECT
DOMAIN-SUFFIX,rtbasia.com,REJECT
DOMAIN-SUFFIX,rubiconproject.com,REJECT
DOMAIN-SUFFIX,scorecardresearch.com,REJECT
DOMAIN-SUFFIX,sdkclick.com,REJECT
DOMAIN-SUFFIX,shuzilm.cn,REJECT
DOMAIN-SUFFIX,smaato.net,REJECT
DOMAIN-SUFFIX,smartadserver.com,REJECT
DOMAIN-SUFFIX,smartnews-ads.com,REJECT
DOMAIN-SUFFIX,supersonic.com,REJECT
DOMAIN-SUFFIX,supersonicads.com,REJECT
DOMAIN-SUFFIX,tagtic.cn,REJECT
DOMAIN-SUFFIX,tanv.com,REJECT
DOMAIN-SUFFIX,tanx.com,REJECT
DOMAIN-SUFFIX,tapjoy.com,REJECT
DOMAIN-SUFFIX,trafficjunky.net,REJECT
DOMAIN-SUFFIX,turn.com,REJECT
DOMAIN-SUFFIX,uri6.com,REJECT
DOMAIN-SUFFIX,vidoomy.com,REJECT
DOMAIN-SUFFIX,voicefive.com,REJECT
DOMAIN-SUFFIX,vungle.com,REJECT
DOMAIN-SUFFIX,wedolook.com,REJECT
DOMAIN-SUFFIX,xdrig.com,REJECT
DOMAIN-SUFFIX,zu08e.cn,REJECT

DOMAIN-SUFFIX,ad.daum.net,REJECT
DOMAIN-SUFFIX,track.xiachufang.com,REJECT
DOMAIN,abema-adx.ameba.jp,REJECT
DOMAIN,ad.12306.cn,REJECT
DOMAIN,ad.360in.com,REJECT
DOMAIN,ad.51wnl-cq.com,REJECT
DOMAIN,ad.caiyunapp.com,REJECT
DOMAIN,ad.huajiao.com,REJECT
DOMAIN,ad.hzyoka.com,REJECT
DOMAIN,ad.jiemian.com,REJECT
DOMAIN,ad.qingting.fm,REJECT
DOMAIN,ad.wappalyzer.com,REJECT
DOMAIN,ad-cn.jovcloud.com,REJECT
DOMAIN,adextra.51wnl-cq.com,REJECT
DOMAIN,ads.adadapted.com,REJECT
DOMAIN,ads.daydaycook.com.cn,REJECT
DOMAIN,ads.weilitoutiao.net,REJECT
DOMAIN,adsapi.manhuaren.com,REJECT
DOMAIN,adsdk.dmzj.com,REJECT
DOMAIN,adserver.pandora.com,REJECT
DOMAIN,adui.tg.meitu.com,REJECT
DOMAIN,adv.bandi.so,REJECT
DOMAIN,adxserver.ad.cmvideo.cn,REJECT
DOMAIN,app-ad.variflight.com,REJECT
DOMAIN,applog.mobike.com,REJECT
DOMAIN,appnext.hs.llnwd.net,REJECT
DOMAIN,appnext-a.akamaihd.net,REJECT
DOMAIN,ggs.myzaker.com,REJECT
DOMAIN,gs.getui.com,REJECT
DOMAIN,itad.linetv.tw,REJECT
DOMAIN,ja.chushou.tv,REJECT
DOMAIN,log.b612kaji.com,REJECT
DOMAIN,mads.suning.com,REJECT
DOMAIN,mobileads.msn.com,REJECT
DOMAIN,mopnativeadv.037201.com,REJECT
DOMAIN,nativeadv.dftoutiao.com,REJECT
DOMAIN,sugar.zhihu.com,REJECT
DOMAIN,toots-a.akamaihd.net,REJECT
DOMAIN,track.tiara.daum.net,REJECT
DOMAIN,track.tiara.kakao.com,REJECT
DOMAIN,trackapp.guahao.cn,REJECT
DOMAIN,traffic.mogujie.com,REJECT
DOMAIN,wmlog.meituan.com,REJECT

# (0~9)
# > 58 同城
DOMAIN,adshow.58.com,REJECT
DOMAIN,track.58.com,REJECT
DOMAIN,tracklog.58.com,REJECT
# (A)
# > Apple
DOMAIN-SUFFIX,iadsdk.apple.com,REJECT
DOMAIN-SUFFIX,ads.internal.unity3d.com,REJECT
DOMAIN-SUFFIX,ads.prd.ie.internal.unity3d.com,REJECT
DOMAIN-SUFFIX,unityads.unity3d.com,REJECT
# > Alibaba
DOMAIN,acs4baichuan.m.taobao.com,REJECT
DOMAIN,adash.m.taobao.com,REJECT
DOMAIN,adash.man.aliyuncs.com,REJECT
DOMAIN,adashbc.ut.taobao.com,REJECT
DOMAIN,adash-c.ut.taobao.com,REJECT
DOMAIN,adashx.m.taobao.com,REJECT
DOMAIN,adashx4yt.m.taobao.com,REJECT
DOMAIN,adashxgc.ut.taobao.com,REJECT
DOMAIN,h-adashx.ut.taobao.com,REJECT
DOMAIN,nbsdk-baichuan.alicdn.com,REJECT
DOMAIN,optimus-ads.amap.com,REJECT
DOMAIN,optimus-ads.amap.com.w.alikunlun.com,REJECT
DOMAIN,tunion-api.m.taobao.com,REJECT
# > AutoHome
DOMAIN,adproxy.autohome.com.cn,REJECT
DOMAIN,rd.autohome.com.cn,REJECT
DOMAIN,al.autohome.com.cn,REJECT
DOMAIN,applogapi.autohome.com.cn,REJECT
# (B)
# > Baidu
DOMAIN-SUFFIX,baidustatic.com,REJECT
DOMAIN-SUFFIX,cpro.baidu.com,REJECT
DOMAIN-SUFFIX,pos.baidu.com,REJECT
DOMAIN,afd.baidu.com,REJECT
DOMAIN,als.baidu.com,REJECT
DOMAIN,duclick.baidu.com,REJECT
DOMAIN,hm.baidu.com,REJECT
DOMAIN,hmma.baidu.com,REJECT
DOMAIN,mobads.baidu.com,REJECT
DOMAIN,mobads-logs.baidu.com,REJECT
DOMAIN,nsclick.baidu.com,REJECT
# > ByteDance
DOMAIN,ad.toutiao.com,REJECT
DOMAIN,applog.musical.ly,REJECT
DOMAIN,track.toutiao.com,REJECT
DOMAIN,xlog.snssdk.com,REJECT
DOMAIN,xlog-va.byteoversea.com,REJECT
# > BitAuto
DOMAIN,adx.yiche.com,REJECT
DOMAIN,log.ycapp.yiche.com,REJECT
# > 百词斩
DOMAIN,advertise.baicizhan.com,REJECT
DOMAIN,advertise.baicizhan.org,REJECT
# (C)
# > CNTV
DOMAIN,galaxy.bjcathay.com,REJECT
DOMAIN,mdrecv.app.cntvwb.cn,REJECT
DOMAIN,sdapprecv.app.cntvwb.cn,REJECT
DOMAIN,vdapprecv.app.cntvwb.cn,REJECT
# > ChinaTelecom
DOMAIN,ad.k.21cn.com,REJECT
DOMAIN,admarket.21cn.com,REJECT
DOMAIN,adshows.21cn.com,REJECT
# > 车来了
DOMAIN,atrace.chelaile.net.cn,REJECT
DOMAIN,logs.chelaile.net.cn,REJECT
# (G)
# > Google
DOMAIN-SUFFIX,doubleclick.net,REJECT
DOMAIN-SUFFIX,googleadservices.com,REJECT
DOMAIN-SUFFIX,googleadsserving.cn,REJECT
DOMAIN-SUFFIX,googlesyndication.com,REJECT
DOMAIN-SUFFIX,googletagmanager.com,REJECT
DOMAIN-SUFFIX,googletagservices.com,REJECT
# (H)
# > HunanTV
DOMAIN-SUFFIX,da.mgtv.com,REJECT
DOMAIN-SUFFIX,da.hunantv.com,REJECT
DOMAIN-SUFFIX,log.hunantv.com,REJECT
DOMAIN,log.v2.hunantv.com,REJECT
DOMAIN,v2.log.hunantv.com,REJECT
# > Hupu
DOMAIN,adx.hupu.com,REJECT
DOMAIN,adx-api.hupu.com,REJECT
DOMAIN,goblin.hupu.com,REJECT
# (I)
# > iQiyi
DOMAIN,ifacelog.iqiyi.com,REJECT
DOMAIN,msg.71.am,REJECT
DOMAIN,msg.qy.net,REJECT
DOMAIN,t7z.cupid.iqiyi.com,REJECT
IP-CIDR,101.227.97.240/32,REJECT,no-resolve
IP-CIDR,101.227.200.11/32,REJECT,no-resolve
IP-CIDR,101.227.200.28/32,REJECT,no-resolve
IP-CIDR,124.192.153.42/32,REJECT,no-resolve
# > Ifeng
DOMAIN-SUFFIX,deliver.ifeng.com,REJECT
DOMAIN,api.newad.ifeng.com,REJECT
DOMAIN,ifengad.3g.ifeng.com,REJECT
# (K)
# > KuGou and Kuwo
DOMAIN,adserviceretry.kugou.com,REJECT
DOMAIN,ads.service.kugou.com,REJECT
DOMAIN,adsfile.bssdlbig.kugou.com,REJECT
DOMAIN,g.koowo.com,REJECT
DOMAIN,kgmobilestat.kugou.com,REJECT
DOMAIN,kgmobilestatbak.kugou.com,REJECT
DOMAIN,mobilelog.kugou.com,REJECT
DOMAIN,mobilead.kuwo.cn,REJECT
DOMAIN,rich.kuwo.cn,REJECT
# > Kingsoft
DOMAIN,ad-stat.ksosoft.com,REJECT
DOMAIN,img.auction-ads.wpscdn.cn,REJECT
DOMAIN,counter.kingsoft.com,REJECT
DOMAIN,counter.ksosoft.com,REJECT
DOMAIN,minfo.wps.cn,REJECT
DOMAIN,mobad.ijinshan.com,REJECT
DOMAIN,ups.ksmobile.net,REJECT
DOMAIN,ws.ksmobile.net,REJECT
# (L)
# > Le
DOMAIN-SUFFIX,webp2p.letv.com,REJECT
DOMAIN,ark.letv.com,REJECT
DOMAIN,emma-414870e223.huodonghezi.com,REJECT
DOMAIN,g3.letv.com,REJECT
DOMAIN,n.mark.letv.com,REJECT
# > 乐播投屏
DOMAIN,ad.hpplay.cn,REJECT
DOMAIN,adeng.hpplay.cn,REJECT
DOMAIN,rp.hpplay.cn,REJECT
# (M)
# > MI
DOMAIN-SUFFIX,ad.intl.xiaomi.com,REJECT
DOMAIN-SUFFIX,ad.xiaomi.com,REJECT
DOMAIN-SUFFIX,admob.xiaomi.com,REJECT
DOMAIN-SUFFIX,tracking.miui.com,REJECT
DOMAIN,adv.sec.intl.miui.com,REJECT
DOMAIN,adv.sec.miui.com,REJECT
DOMAIN,data.mistat.xiaomi.com,REJECT
DOMAIN,tracking.intl.miui.com,REJECT
# > 墨迹天气
DOMAIN,ad.api.moji.com,REJECT
DOMAIN,adlaunch.moji.com,REJECT
DOMAIN,ads.mojicdn.com,REJECT
DOMAIN,v1.log.moji.com,REJECT
# (N)
# > NetEase
DOMAIN,ad.bn.netease.com,REJECT
DOMAIN,ad.yixin.im,REJECT
DOMAIN,admusicpic.music.126.net,REJECT
DOMAIN,gorgon.youdao.com,REJECT
DOMAIN,iadmat.nosdn.127.net,REJECT
DOMAIN,iadmusicmat.music.126.net,REJECT
DOMAIN,iadmusicmatvideo.music.126.net,REJECT
DOMAIN,impservice.dictapp.youdao.com,REJECT
DOMAIN,impservice.youdao.com,REJECT
DOMAIN,log.yex.youdao.com,REJECT
DOMAIN,log-yex.youdao.com,REJECT
DOMAIN,n.3g.163.com,REJECT
DOMAIN,nex.163.com,REJECT
DOMAIN,yt-adp.nosdn.127.net,REJECT
DOMAIN,yt-adp.ws.126.net,REJECT
# (P)
# > PPTV
DOMAIN,ads.aplus.pptv.com,REJECT
DOMAIN,ads.aplusapi.pptv.com,REJECT
DOMAIN,asimgs.pplive.cn,REJECT
DOMAIN,de.as.pptv.com,REJECT
# > Photoable
DOMAIN,regist.fotoable.com,REJECT
DOMAIN,cdn.adapi.fotoable.com,REJECT
# > PeanutWiFiMpass
DOMAIN,adnew.wifi8.com,REJECT
DOMAIN,adfile.wifi8.com,REJECT
# (S)
# > Sina
DOMAIN-SUFFIX,beacon.sina.com.cn,REJECT
DOMAIN,adimg.vue.weibo.com,REJECT
DOMAIN,u1.img.mobile.sina.cn,REJECT
DOMAIN,sax.sina.com.cn,REJECT
DOMAIN,saxs.sina.com.cn,REJECT
DOMAIN,saxn.sina.com.cn,REJECT
# > Sohu
DOMAIN-SUFFIX,ad.sohu.com,REJECT
DOMAIN-SUFFIX,ads.sohu.com,REJECT
DOMAIN-SUFFIX,aty.sohu.com,REJECT
DOMAIN,imp.optaim.com,REJECT
DOMAIN,v2.reachmax.cn,REJECT
DOMAIN,track.sohu.com,REJECT
DOMAIN,hui.sohu.com,REJECT
# (T)
# > Tencent
DOMAIN-SUFFIX,beacon.qq.com,REJECT
DOMAIN-SUFFIX,bugly.qq.com,REJECT
DOMAIN-SUFFIX,e.qq.com,REJECT
DOMAIN-SUFFIX,gdt.qq.com,REJECT
DOMAIN-SUFFIX,l.qq.com,REJECT
DOMAIN-SUFFIX,rqd.qq.com,REJECT
DOMAIN,adsmind.tc.qq.com,REJECT
DOMAIN,adsmind.apdcdn.tc.qq.com,REJECT
DOMAIN,btrace.qq.com,REJECT
DOMAIN,mtrace.qq.com,REJECT
DOMAIN,oth.eve.mdt.qq.com,REJECT
DOMAIN,pgdt.gtimg.com,REJECT
DOMAIN,pgdt.gtimg.cn,REJECT
DOMAIN,pgdt.ugdtimg.com,REJECT
DOMAIN,pingma.qq.com,REJECT
DOMAIN,pingtcss.qq.com,REJECT
DOMAIN,splashqqlive.gtimg.com,REJECT
DOMAIN,tajs.qq.com,REJECT
DOMAIN,wxsnsdy.wxs.qq.com,REJECT
DOMAIN,wxsnsdythumb.wxs.qq.com,REJECT
# > The Paper
DOMAIN,admonitor.thepaper.cn,REJECT
DOMAIN,adpai.thepaper.cn,REJECT
DOMAIN,imgadpai.thepaper.cn,REJECT
# > Thunder
DOMAIN,adsp.xunlei.com,REJECT
DOMAIN,etl.xlmc.sandai.net,REJECT
# > 同花顺
DOMAIN,adm.10jqka.com.cn,REJECT
DOMAIN,stat.10jqka.com.cn,REJECT
# > 太平洋
DOMAIN,ad-analysis.pconline.com.cn,REJECT
DOMAIN,iad0ssl.pcauto.com.cn,REJECT
DOMAIN,iad0ssl.pconline.com.cn,REJECT
DOMAIN,imgad0.pcauto.com.cn,REJECT
DOMAIN,imgad0.pconline.com.cn,REJECT
DOMAIN,ivy.pchouse.com.cn,REJECT
# (U)
# > UC
DOMAIN,adtrack.ucweb.com,REJECT
DOMAIN,track.uc.cn,REJECT
# > Umeng
DOMAIN,alog.umeng.co,REJECT
DOMAIN,alog.umeng.com,REJECT
DOMAIN,alogs.umeng.com,REJECT
DOMAIN,alog.umengcloud.com,REJECT
DOMAIN,alogs.umengcloud.com,REJECT
DOMAIN,ar.umeng.com,REJECT
DOMAIN,plbslog.umeng.com,REJECT
DOMAIN,ulogs.umeng.com,REJECT
DOMAIN,ulogs.umengcloud.com,REJECT
# (W)
# > WiFi 万能钥匙
DOMAIN,a.wkanx.com,REJECT
DOMAIN,cwx.lianwangtech.com,REJECT
DOMAIN,c1wx.lianwangtech.com,REJECT
# (X)
# > 喜马拉雅
DOMAIN,ad.ximalaya.com,REJECT
DOMAIN,adbs.ximalaya.com,REJECT
DOMAIN,adse.ximalaya.com,REJECT
DOMAIN,adse.wsa.ximalaya.com,REJECT
DOMAIN,adbehavior.wsa.ximalaya.com,REJECT
DOMAIN,adsebs.ximalaya.com,REJECT
# > 小红书
DOMAIN,ads-video-qc.xhscdn.com,REJECT
DOMAIN,apm-track.xiaohongshu.com,REJECT
DOMAIN,t-ads.xiaohongshu.com,REJECT
# (Y)
# > Youku
DOMAIN-SUFFIX,atm.youku.com,REJECT
DOMAIN,ad.mobile.youku.com,REJECT
DOMAIN,iyes.youku.com,REJECT
# (Z)
# > ZOL
DOMAIN,apppv.zol.com.cn,REJECT
DOMAIN,pvnapp.zol.com.cn,REJECT

# Internet Service Providers Hijacking 运营商劫持
DOMAIN-SUFFIX,17gouwuba.com,REJECT
DOMAIN-SUFFIX,186078.com,REJECT
DOMAIN-SUFFIX,189zj.cn,REJECT
DOMAIN-SUFFIX,285680.com,REJECT
DOMAIN-SUFFIX,3721zh.com,REJECT
DOMAIN-SUFFIX,4336wang.cn,REJECT
DOMAIN-SUFFIX,51chumoping.com,REJECT
DOMAIN-SUFFIX,51mld.cn,REJECT
DOMAIN-SUFFIX,51mypc.cn,REJECT
DOMAIN-SUFFIX,58mingri.cn,REJECT
DOMAIN-SUFFIX,58mingtian.cn,REJECT
DOMAIN-SUFFIX,5vl58stm.com,REJECT
DOMAIN-SUFFIX,6d63d3.com,REJECT
DOMAIN-SUFFIX,7gg.cc,REJECT
DOMAIN-SUFFIX,91veg.com,REJECT
DOMAIN-SUFFIX,9s6q.cn,REJECT
DOMAIN-SUFFIX,adsame.com,REJECT
DOMAIN-SUFFIX,aiclk.com,REJECT
DOMAIN-SUFFIX,akuai.top,REJECT
DOMAIN-SUFFIX,atplay.cn,REJECT
DOMAIN-SUFFIX,baiwanchuangyi.com,REJECT
DOMAIN-SUFFIX,beerto.cn,REJECT
DOMAIN-SUFFIX,beilamusi.com,REJECT
DOMAIN-SUFFIX,benshiw.net,REJECT
DOMAIN-SUFFIX,bianxianmao.com,REJECT
DOMAIN-SUFFIX,bryonypie.com,REJECT
DOMAIN-SUFFIX,cishantao.com,REJECT
DOMAIN-SUFFIX,cszlks.com,REJECT
DOMAIN-SUFFIX,cudaojia.com,REJECT
DOMAIN-SUFFIX,dafapromo.com,REJECT
DOMAIN-SUFFIX,daitdai.com,REJECT
DOMAIN-SUFFIX,dsaeerf.com,REJECT
DOMAIN-SUFFIX,dugesheying.com,REJECT
DOMAIN-SUFFIX,dv8c1t.cn,REJECT
DOMAIN-SUFFIX,echatu.com,REJECT
DOMAIN-SUFFIX,erdoscs.com,REJECT
DOMAIN-SUFFIX,fan-yong.com,REJECT
DOMAIN-SUFFIX,feih.com.cn,REJECT
DOMAIN-SUFFIX,fjlqqc.com,REJECT
DOMAIN-SUFFIX,fkku194.com,REJECT
DOMAIN-SUFFIX,freedrive.cn,REJECT
DOMAIN-SUFFIX,gclick.cn,REJECT
DOMAIN-SUFFIX,goufanli100.com,REJECT
DOMAIN-SUFFIX,goupaoerdai.com,REJECT
DOMAIN-SUFFIX,gouwubang.com,REJECT
DOMAIN-SUFFIX,gzxnlk.com,REJECT
DOMAIN-SUFFIX,haoshengtoys.com,REJECT
DOMAIN-SUFFIX,hyunke.com,REJECT
DOMAIN-SUFFIX,ichaosheng.com,REJECT
DOMAIN-SUFFIX,ishop789.com,REJECT
DOMAIN-SUFFIX,jdkic.com,REJECT
DOMAIN-SUFFIX,jiubuhua.com,REJECT
DOMAIN-SUFFIX,jsncke.com,REJECT
DOMAIN-SUFFIX,junkucm.com,REJECT
DOMAIN-SUFFIX,jwg365.cn,REJECT
DOMAIN-SUFFIX,kawo77.com,REJECT
DOMAIN-SUFFIX,kualianyingxiao.cn,REJECT
DOMAIN-SUFFIX,kumihua.com,REJECT
DOMAIN-SUFFIX,ltheanine.cn,REJECT
DOMAIN-SUFFIX,maipinshangmao.com,REJECT
DOMAIN-SUFFIX,minisplat.cn,REJECT
DOMAIN-SUFFIX,mkitgfs.com,REJECT
DOMAIN-SUFFIX,mlnbike.com,REJECT
DOMAIN-SUFFIX,mobjump.com,REJECT
DOMAIN-SUFFIX,nbkbgd.cn,REJECT
DOMAIN-SUFFIX,newapi.com,REJECT
DOMAIN-SUFFIX,pinzhitmall.com,REJECT
DOMAIN-SUFFIX,poppyta.com,REJECT
DOMAIN-SUFFIX,qianchuanghr.com,REJECT
DOMAIN-SUFFIX,qichexin.com,REJECT
DOMAIN-SUFFIX,qinchugudao.com,REJECT
DOMAIN-SUFFIX,quanliyouxi.cn,REJECT
DOMAIN-SUFFIX,qutaobi.com,REJECT
DOMAIN-SUFFIX,ry51w.cn,REJECT
DOMAIN-SUFFIX,sg536.cn,REJECT
DOMAIN-SUFFIX,sifubo.cn,REJECT
DOMAIN-SUFFIX,sifuce.cn,REJECT
DOMAIN-SUFFIX,sifuda.cn,REJECT
DOMAIN-SUFFIX,sifufu.cn,REJECT
DOMAIN-SUFFIX,sifuge.cn,REJECT
DOMAIN-SUFFIX,sifugu.cn,REJECT
DOMAIN-SUFFIX,sifuhe.cn,REJECT
DOMAIN-SUFFIX,sifuhu.cn,REJECT
DOMAIN-SUFFIX,sifuji.cn,REJECT
DOMAIN-SUFFIX,sifuka.cn,REJECT
DOMAIN-SUFFIX,smgru.net,REJECT
DOMAIN-SUFFIX,taoggou.com,REJECT
DOMAIN-SUFFIX,tcxshop.com,REJECT
DOMAIN-SUFFIX,tjqonline.cn,REJECT
DOMAIN-SUFFIX,topitme.com,REJECT
DOMAIN-SUFFIX,tt3sm4.cn,REJECT
DOMAIN-SUFFIX,tuia.cn,REJECT
DOMAIN-SUFFIX,tuipenguin.com,REJECT
DOMAIN-SUFFIX,tuitiger.com,REJECT
DOMAIN-SUFFIX,websd8.com,REJECT
DOMAIN-SUFFIX,wsgblw.com,REJECT
DOMAIN-SUFFIX,wx16999.com,REJECT
DOMAIN-SUFFIX,xchmai.com,REJECT
DOMAIN-SUFFIX,xiaohuau.xyz,REJECT
DOMAIN-SUFFIX,ygyzx.cn,REJECT
DOMAIN-SUFFIX,yinmong.com,REJECT
DOMAIN-SUFFIX,yitaopt.com,REJECT
DOMAIN-SUFFIX,yjqiqi.com,REJECT
DOMAIN-SUFFIX,yukhj.com,REJECT
DOMAIN-SUFFIX,zhaozecheng.cn,REJECT
DOMAIN-SUFFIX,zhenxinet.com,REJECT
DOMAIN-SUFFIX,zlne800.com,REJECT
DOMAIN-SUFFIX,zunmi.cn,REJECT
DOMAIN-SUFFIX,zzd6.com,REJECT
IP-CIDR,39.107.15.115/32,REJECT,no-resolve
IP-CIDR,47.89.59.182/32,REJECT,no-resolve
IP-CIDR,103.49.209.27/32,REJECT,no-resolve
IP-CIDR,123.56.152.96/32,REJECT,no-resolve
# > ChinaTelecom
IP-CIDR,61.160.200.223/32,REJECT,no-resolve
IP-CIDR,61.160.200.242/32,REJECT,no-resolve
IP-CIDR,61.160.200.252/32,REJECT,no-resolve
IP-CIDR,61.174.50.214/32,REJECT,no-resolve
IP-CIDR,111.175.220.163/32,REJECT,no-resolve
IP-CIDR,111.175.220.164/32,REJECT,no-resolve
IP-CIDR,122.229.8.47/32,REJECT,no-resolve
IP-CIDR,122.229.29.89/32,REJECT,no-resolve
IP-CIDR,124.232.160.178/32,REJECT,no-resolve
IP-CIDR,175.6.223.15/32,REJECT,no-resolve
IP-CIDR,183.59.53.237/32,REJECT,no-resolve
IP-CIDR,218.93.127.37/32,REJECT,no-resolve
IP-CIDR,221.228.17.152/32,REJECT,no-resolve
IP-CIDR,221.231.6.79/32,REJECT,no-resolve
IP-CIDR,222.186.61.91/32,REJECT,no-resolve
IP-CIDR,222.186.61.95/32,REJECT,no-resolve
IP-CIDR,222.186.61.96/32,REJECT,no-resolve
IP-CIDR,222.186.61.97/32,REJECT,no-resolve
# > ChinaUnicom
IP-CIDR,106.75.231.48/32,REJECT,no-resolve
IP-CIDR,119.4.249.166/32,REJECT,no-resolve
IP-CIDR,220.196.52.141/32,REJECT,no-resolve
IP-CIDR,221.6.4.148/32,REJECT,no-resolve
# > ChinaMobile
IP-CIDR,114.247.28.96/32,REJECT,no-resolve
IP-CIDR,221.179.131.72/32,REJECT,no-resolve
IP-CIDR,221.179.140.145/32,REJECT,no-resolve
# > Dr.Peng
# IP-CIDR,10.72.25.0/24,REJECT,no-resolve
IP-CIDR,115.182.16.79/32,REJECT,no-resolve
IP-CIDR,118.144.88.126/32,REJECT,no-resolve
IP-CIDR,118.144.88.215/32,REJECT,no-resolve
IP-CIDR,118.144.88.216/32,REJECT,no-resolve
IP-CIDR,120.76.189.132/32,REJECT,no-resolve
IP-CIDR,124.14.21.147/32,REJECT,no-resolve
IP-CIDR,124.14.21.151/32,REJECT,no-resolve
IP-CIDR,180.166.52.24/32,REJECT,no-resolve
IP-CIDR,211.161.101.106/32,REJECT,no-resolve
IP-CIDR,220.115.251.25/32,REJECT,no-resolve
IP-CIDR,222.73.156.235/32,REJECT,no-resolve

# Malware 恶意网站
# > 快压
# https://zhuanlan.zhihu.com/p/39534279
DOMAIN-SUFFIX,kuaizip.com,REJECT
# > MacKeeper
# https://www.lizhi.io/blog/40002904
DOMAIN-SUFFIX,mackeeper.com,REJECT
DOMAIN-SUFFIX,zryydi.com,REJECT
# > Adobe Flash China Special Edition
# https://www.zhihu.com/question/281163698/answer/441388130
DOMAIN-SUFFIX,flash.cn,REJECT
DOMAIN,geo2.adobe.com,REJECT
# > C&J Marketing 思杰马克丁软件
# https://www.zhihu.com/question/46746200
DOMAIN-SUFFIX,4009997658.com,REJECT
DOMAIN-SUFFIX,abbyychina.com,REJECT
DOMAIN-SUFFIX,bartender.cc,REJECT
DOMAIN-SUFFIX,betterzip.net,REJECT
DOMAIN-SUFFIX,betterzipcn.com,REJECT
DOMAIN-SUFFIX,beyondcompare.cc,REJECT
DOMAIN-SUFFIX,bingdianhuanyuan.cn,REJECT
DOMAIN-SUFFIX,chemdraw.com.cn,REJECT
DOMAIN-SUFFIX,cjmakeding.com,REJECT
DOMAIN-SUFFIX,cjmkt.com,REJECT
DOMAIN-SUFFIX,codesoftchina.com,REJECT
DOMAIN-SUFFIX,coreldrawchina.com,REJECT
DOMAIN-SUFFIX,crossoverchina.com,REJECT
DOMAIN-SUFFIX,dongmansoft.com,REJECT
DOMAIN-SUFFIX,earmasterchina.cn,REJECT
DOMAIN-SUFFIX,easyrecoverychina.com,REJECT
DOMAIN-SUFFIX,ediuschina.com,REJECT
DOMAIN-SUFFIX,flstudiochina.com,REJECT
DOMAIN-SUFFIX,formysql.com,REJECT
DOMAIN-SUFFIX,guitarpro.cc,REJECT
DOMAIN-SUFFIX,huishenghuiying.com.cn,REJECT
DOMAIN-SUFFIX,hypersnap.net,REJECT
DOMAIN-SUFFIX,iconworkshop.cn,REJECT
DOMAIN-SUFFIX,imindmap.cc,REJECT
DOMAIN-SUFFIX,jihehuaban.com.cn,REJECT
DOMAIN-SUFFIX,keyshot.cc,REJECT
DOMAIN-SUFFIX,kingdeecn.cn,REJECT
DOMAIN-SUFFIX,logoshejishi.com,REJECT
DOMAIN-SUFFIX,luping.net.cn,REJECT
DOMAIN-SUFFIX,mairuan.cn,REJECT
DOMAIN-SUFFIX,mairuan.com,REJECT
DOMAIN-SUFFIX,mairuan.com.cn,REJECT
DOMAIN-SUFFIX,mairuan.net,REJECT
DOMAIN-SUFFIX,mairuanwang.com,REJECT
DOMAIN-SUFFIX,makeding.com,REJECT
DOMAIN-SUFFIX,mathtype.cn,REJECT
DOMAIN-SUFFIX,mindmanager.cc,REJECT
DOMAIN-SUFFIX,mindmanager.cn,REJECT
DOMAIN-SUFFIX,mindmapper.cc,REJECT
DOMAIN-SUFFIX,mycleanmymac.com,REJECT
DOMAIN-SUFFIX,nicelabel.cc,REJECT
DOMAIN-SUFFIX,ntfsformac.cc,REJECT
DOMAIN-SUFFIX,ntfsformac.cn,REJECT
DOMAIN-SUFFIX,overturechina.com,REJECT
DOMAIN-SUFFIX,passwordrecovery.cn,REJECT
DOMAIN-SUFFIX,pdfexpert.cc,REJECT
DOMAIN-SUFFIX,photozoomchina.com,REJECT
DOMAIN-SUFFIX,shankejingling.com,REJECT
DOMAIN-SUFFIX,ultraiso.net,REJECT
DOMAIN-SUFFIX,vegaschina.cn,REJECT
DOMAIN-SUFFIX,xmindchina.net,REJECT
DOMAIN-SUFFIX,xshellcn.com,REJECT
DOMAIN-SUFFIX,yihuifu.cn,REJECT
DOMAIN-SUFFIX,yuanchengxiezuo.com,REJECT
DOMAIN-SUFFIX,zbrushcn.com,REJECT
DOMAIN-SUFFIX,zhzzx.com,REJECT

# Global Area Network
# (GlobalMedia)
# (Music)
# > Deezer
USER-AGENT,Deezer*,Deezer 专用节点
DOMAIN-SUFFIX,deezer.com,Deezer 专用节点,force-remote-dns
DOMAIN-SUFFIX,dzcdn.net,Deezer 专用节点
# > KKBOX
DOMAIN-SUFFIX,kkbox.com,KKBOX 专用节点
DOMAIN-SUFFIX,kkbox.com.tw,KKBOX 专用节点
DOMAIN-SUFFIX,kfs.io,KKBOX 专用节点
# > JOOX
USER-AGENT,WeMusic*,JOOX 专用节点
USER-AGENT,JOOX*,JOOX 专用节点
DOMAIN-SUFFIX,joox.com,JOOX 专用节点
# > Pandora
USER-AGENT,Pandora*,Pandora 专用节点
DOMAIN-SUFFIX,pandora.com,Pandora 专用节点
# > SoundCloud
USER-AGENT,SoundCloud*,SoundCloud 专用节点
DOMAIN-SUFFIX,p-cdn.us,SoundCloud 专用节点
DOMAIN-SUFFIX,sndcdn.com,SoundCloud 专用节点
DOMAIN-SUFFIX,soundcloud.com,SoundCloud 专用节点,force-remote-dns
# > Spotify
USER-AGENT,Spotify*,Spotify 专用节点
DOMAIN-SUFFIX,pscdn.co,Spotify 专用节点
DOMAIN-SUFFIX,scdn.co,Spotify 专用节点
DOMAIN-SUFFIX,spotify.com,Spotify 专用节点
DOMAIN-SUFFIX,spoti.fi,Spotify 专用节点
DOMAIN-KEYWORD,spotify.com,Spotify 专用节点
DOMAIN-KEYWORD,-spotify-com,Spotify 专用节点
# > TIDAL
USER-AGENT,TIDAL*,TIDAL 专用节点
DOMAIN-SUFFIX,tidal.com,TIDAL 专用节点
# > YouTubeMusic
USER-AGENT,com.google.ios.youtubemusic*,YouTubeMusic 专用节点
USER-AGENT,YouTubeMusic*,YouTubeMusic 专用节点
# (Video)
# > All4
USER-AGENT,All4*,All4 专用节点
DOMAIN-SUFFIX,c4assets.com,All4 专用节点
DOMAIN-SUFFIX,channel4.com,All4 专用节点
# > AbemaTV
USER-AGENT,AbemaTV*,AbemaTV 专用节点
DOMAIN-SUFFIX,abema.io,AbemaTV 专用节点
DOMAIN-SUFFIX,ameba.jp,AbemaTV 专用节点
DOMAIN-SUFFIX,abema.tv,AbemaTV 专用节点
DOMAIN-SUFFIX,hayabusa.io,AbemaTV 专用节点
DOMAIN,abematv.akamaized.net,AbemaTV 专用节点
DOMAIN,ds-linear-abematv.akamaized.net,AbemaTV 专用节点
DOMAIN,ds-vod-abematv.akamaized.net,AbemaTV 专用节点
DOMAIN,linear-abematv.akamaized.net,AbemaTV 专用节点
# > Amazon Prime Video
USER-AGENT,InstantVideo.US*,Prime Video 专用节点
USER-AGENT,Prime%20Video*,Prime Video 专用节点
DOMAIN-SUFFIX,aiv-cdn.net,Prime Video 专用节点
DOMAIN-SUFFIX,aiv-delivery.net,Prime Video 专用节点
DOMAIN-SUFFIX,amazonvideo.com,Prime Video 专用节点
DOMAIN-SUFFIX,primevideo.com,Prime Video 专用节点
DOMAIN,avodmp4s3ww-a.akamaihd.net,Prime Video 专用节点
DOMAIN,d25xi40x97liuc.cloudfront.net,Prime Video 专用节点
DOMAIN,dmqdd6hw24ucf.cloudfront.net,Prime Video 专用节点
DOMAIN,d22qjgkvxw22r6.cloudfront.net,Prime Video 专用节点
DOMAIN,d1v5ir2lpwr8os.cloudfront.net,Prime Video 专用节点
DOMAIN-KEYWORD,avoddashs,Prime Video 专用节点
# > Bahamut
USER-AGENT,Anime*,動畫瘋专用节点
DOMAIN-SUFFIX,bahamut.com.tw,動畫瘋专用节点
DOMAIN-SUFFIX,gamer.com.tw,動畫瘋专用节点
DOMAIN,gamer-cds.cdn.hinet.net,動畫瘋专用节点
DOMAIN,gamer2-cds.cdn.hinet.net,動畫瘋专用节点
# > BBC iPlayer
USER-AGENT,BBCiPlayer*,BBC iPlayer 专用节点
DOMAIN-SUFFIX,bbc.co.uk,BBC iPlayer 专用节点,force-remote-dns
DOMAIN-SUFFIX,bbci.co.uk,BBC iPlayer 专用节点,force-remote-dns
DOMAIN-KEYWORD,bbcfmt,BBC iPlayer 专用节点
DOMAIN-KEYWORD,uk-live,BBC iPlayer 专用节点
# > DAZN
USER-AGENT,DAZN*,DAZN 专用节点
DOMAIN-SUFFIX,dazn.com,DAZN 专用节点
DOMAIN-SUFFIX,dazn-api.com,DAZN 专用节点
DOMAIN,d151l6v8er5bdm.cloudfront.net,DAZN 专用节点
DOMAIN-KEYWORD,voddazn,DAZN 专用节点
# > Disney+
USER-AGENT,Disney+*,Disney+ 专用节点
DOMAIN-SUFFIX,bamgrid.com,Disney+ 专用节点
DOMAIN-SUFFIX,disney-plus.net,Disney+ 专用节点
DOMAIN-SUFFIX,disneyplus.com,Disney+ 专用节点
DOMAIN-SUFFIX,dssott.com,Disney+ 专用节点
DOMAIN,cdn.registerdisney.go.com,Disney+ 专用节点
# > encoreTVB
USER-AGENT,encoreTVB*,encoreTVB 专用节点
DOMAIN-SUFFIX,encoretvb.com,encoreTVB 专用节点
DOMAIN,edge.api.brightcove.com,encoreTVB 专用节点
DOMAIN,bcbolt446c5271-a.akamaihd.net,encoreTVB 专用节点
# > FOX NOW
USER-AGENT,FOX%20NOW*,FOX NOW/Plus 专用节点
DOMAIN-SUFFIX,fox.com,FOX NOW/Plus 专用节点
DOMAIN-SUFFIX,foxdcg.com,FOX NOW/Plus 专用节点
DOMAIN-SUFFIX,theplatform.com,FOX NOW/Plus 专用节点
DOMAIN-SUFFIX,uplynk.com,FOX NOW/Plus 专用节点
# > FOXPlus
USER-AGENT,FOXPlus*,FOX NOW/Plus 专用节点
DOMAIN-SUFFIX,foxplus.com,FOX NOW/Plus 专用节点
# DOMAIN-SUFFIX,theplatform.com,FOX NOW/Plus 专用节点
DOMAIN,d3cv4a9a9wh0bt.cloudfront.net,FOX NOW/Plus 专用节点
DOMAIN,staticasiafox.akamaized.net,FOX NOW/Plus 专用节点
DOMAIN,foxsports01-i.akamaihd.net,FOX NOW/Plus 专用节点
DOMAIN,foxsports02-i.akamaihd.net,FOX NOW/Plus 专用节点
DOMAIN,foxsports03-i.akamaihd.net,FOX NOW/Plus 专用节点
DOMAIN,cdn-fox-networks-group-green.akamaized.net,FOX NOW/Plus 专用节点
# > HBO NOW
USER-AGENT,HBO%20NOW*,HBO NOW 专用节点
DOMAIN-SUFFIX,hbo.com,HBO NOW 专用节点
DOMAIN-SUFFIX,hbogo.com,HBO NOW 专用节点
DOMAIN-SUFFIX,hbonow.com,HBO NOW 专用节点
# > HBO GO HKG
USER-AGENT,HBO%20GO%20PROD%20HKG*,HBO GO HKG 专用节点
DOMAIN-SUFFIX,hbogoasia.com,HBO GO HKG 专用节点
DOMAIN-SUFFIX,hbogoasia.hk,HBO GO HKG 专用节点
DOMAIN,bcbolthboa-a.akamaihd.net,HBO GO HKG 专用节点
DOMAIN,players.brightcove.net,HBO GO HKG 专用节点
DOMAIN,s3-ap-southeast-1.amazonaws.com,HBO GO HKG 专用节点
DOMAIN,dai3fd1oh325y.cloudfront.net,HBO GO HKG 专用节点
DOMAIN,44wilhpljf.execute-api.ap-southeast-1.amazonaws.com,HBO GO HKG 专用节点
DOMAIN,hboasia1-i.akamaihd.net,HBO GO HKG 专用节点
DOMAIN,hboasia2-i.akamaihd.net,HBO GO HKG 专用节点
DOMAIN,hboasia3-i.akamaihd.net,HBO GO HKG 专用节点
DOMAIN,hboasia4-i.akamaihd.net,HBO GO HKG 专用节点
DOMAIN,hboasia5-i.akamaihd.net,HBO GO HKG 专用节点
DOMAIN,cf-images.ap-southeast-1.prod.boltdns.net,HBO GO HKG 专用节点
# > 华文电视
USER-AGENT,HWTVMobile*,华文电视专用节点
DOMAIN-SUFFIX,5itv.tv,华文电视专用节点
DOMAIN-SUFFIX,ocnttv.com,华文电视专用节点
# > Hulu
DOMAIN-SUFFIX,hulu.com,Hulu 专用节点
DOMAIN-SUFFIX,huluim.com,Hulu 专用节点
DOMAIN-SUFFIX,hulustream.com,Hulu 专用节点
# > Hulu(フールー)
DOMAIN-SUFFIX,happyon.jp,Hulu(フールー) 专用节点
DOMAIN-SUFFIX,hulu.jp,Hulu(フールー) 专用节点
# > ITV
USER-AGENT,ITV_Player*,ITV 专用节点
DOMAIN-SUFFIX,itv.com,ITV 专用节点
DOMAIN-SUFFIX,itvstatic.com,ITV 专用节点
DOMAIN,itvpnpmobile-a.akamaihd.net,ITV 专用节点
# > KKTV
USER-AGENT,KKTV*,KKTV 专用节点
USER-AGENT,com.kktv.ios.kktv*,KKTV 专用节点
DOMAIN-SUFFIX,kktv.com.tw,KKTV 专用节点
DOMAIN-SUFFIX,kktv.me,KKTV 专用节点
DOMAIN,kktv-theater.kk.stream,KKTV 专用节点
# > Line TV
USER-AGENT,LINE%20TV*,Line TV 专用节点
DOMAIN-SUFFIX,linetv.tw,Line TV 专用节点
DOMAIN,d3c7rimkq79yfu.cloudfront.net,Line TV 专用节点
# > LiTV
DOMAIN-SUFFIX,litv.tv,LiTV 专用节点
DOMAIN,litvfreemobile-hichannel.cdn.hinet.net,LiTV 专用节点
# > My5
USER-AGENT,My5*,My5 专用节点
DOMAIN-SUFFIX,channel5.com,My5 专用节点
DOMAIN-SUFFIX,my5.tv,My5 专用节点
DOMAIN,d349g9zuie06uo.cloudfront.net,My5 专用节点
# > myTV SUPER
USER-AGENT,mytv*,myTV SUPER 专用节点
DOMAIN-SUFFIX,mytvsuper.com,myTV SUPER 专用节点
DOMAIN-SUFFIX,tvb.com,myTV SUPER 专用节点
# > Netflix
USER-AGENT,Argo*,Netflix 专用节点
DOMAIN-SUFFIX,netflix.com,Netflix 专用节点
DOMAIN-SUFFIX,netflix.net,Netflix 专用节点
DOMAIN-SUFFIX,nflxext.com,Netflix 专用节点
DOMAIN-SUFFIX,nflximg.com,Netflix 专用节点
DOMAIN-SUFFIX,nflximg.net,Netflix 专用节点
DOMAIN-SUFFIX,nflxso.net,Netflix 专用节点
DOMAIN-SUFFIX,nflxvideo.net,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest0.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest1.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest2.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest3.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest4.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest5.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest6.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest7.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest8.com,Netflix 专用节点
DOMAIN-SUFFIX,netflixdnstest9.com,Netflix 专用节点
IP-CIDR,23.246.0.0/18,Netflix 专用节点,no-resolve
IP-CIDR,37.77.184.0/21,Netflix 专用节点,no-resolve
IP-CIDR,45.57.0.0/17,Netflix 专用节点,no-resolve
IP-CIDR,64.120.128.0/17,Netflix 专用节点,no-resolve
IP-CIDR,66.197.128.0/17,Netflix 专用节点,no-resolve
IP-CIDR,108.175.32.0/20,Netflix 专用节点,no-resolve
IP-CIDR,192.173.64.0/18,Netflix 专用节点,no-resolve
IP-CIDR,198.38.96.0/19,Netflix 专用节点,no-resolve
IP-CIDR,198.45.48.0/20,Netflix 专用节点,no-resolve
# > niconico
USER-AGENT,Niconico*,niconico 专用节点
DOMAIN-SUFFIX,dmc.nico,niconico 专用节点,force-remote-dns
DOMAIN-SUFFIX,nicovideo.jp,niconico 专用节点,force-remote-dns
DOMAIN-SUFFIX,nimg.jp,niconico 专用节点
DOMAIN-SUFFIX,socdm.com,niconico 专用节点
# > Now E
DOMAIN-SUFFIX,nowe.com,Now E 专用节点
DOMAIN-SUFFIX,nowestatic.com,Now E 专用节点
# > PBS
USER-AGENT,PBS*,PBS 专用节点
DOMAIN-SUFFIX,pbs.org,PBS 专用节点
# > Pornhub
DOMAIN-SUFFIX,phncdn.com,Pornhub 专用节点
DOMAIN-SUFFIX,pornhub.com,Pornhub 专用节点,force-remote-dns
DOMAIN-SUFFIX,pornhubpremium.com,Pornhub 专用节点,force-remote-dns
# > 台湾好
USER-AGENT,TaiwanGood*,台湾好专用节点
DOMAIN-SUFFIX,skyking.com.tw,台湾好专用节点
DOMAIN,hamifans.emome.net,台湾好专用节点
# > Twitch
DOMAIN-SUFFIX,twitch.tv,Twitch 专用节点,force-remote-dns
DOMAIN-SUFFIX,twitchcdn.net,Twitch 专用节点
DOMAIN-SUFFIX,ttvnw.net,Twitch 专用节点
DOMAIN-SUFFIX,jtvnw.net,Twitch 专用节点
# > ViuTV
USER-AGENT,Viu*,ViuTV 专用节点
USER-AGENT,ViuTV*,ViuTV 专用节点
DOMAIN-SUFFIX,viu.com,ViuTV 专用节点
DOMAIN-SUFFIX,viu.tv,ViuTV 专用节点
DOMAIN,api.viu.now.com,ViuTV 专用节点
DOMAIN,d1k2us671qcoau.cloudfront.net,ViuTV 专用节点
DOMAIN,d2anahhhmp1ffz.cloudfront.net,ViuTV 专用节点
DOMAIN,dfp6rglgjqszk.cloudfront.net,ViuTV 专用节点
# > YouTube
USER-AGENT,com.google.ios.youtube*,YouTube 专用节点
USER-AGENT,YouTube*,YouTube 专用节点
DOMAIN-SUFFIX,googlevideo.com,YouTube 专用节点,force-remote-dns
DOMAIN-SUFFIX,youtube.com,YouTube 专用节点,force-remote-dns
DOMAIN,youtubei.googleapis.com,YouTube 专用节点,force-remote-dns

# (DNS Cache Pollution Protection)
# > Google
DOMAIN-SUFFIX,ampproject.org,Google 专用节点,force-remote-dns
DOMAIN-SUFFIX,appspot.com,Google 专用节点,force-remote-dns
DOMAIN-SUFFIX,blogger.com,Google 专用节点,force-remote-dns
DOMAIN-SUFFIX,getoutline.org,Google 专用节点,force-remote-dns
DOMAIN-SUFFIX,gvt0.com,Google 专用节点,force-remote-dns
DOMAIN-SUFFIX,gvt1.com,Google 专用节点,force-remote-dns
DOMAIN-SUFFIX,gvt3.com,Google 专用节点,force-remote-dns
DOMAIN-SUFFIX,xn--ngstr-lra8j.com,Google 专用节点,force-remote-dns
DOMAIN-KEYWORD,google,Google 专用节点,force-remote-dns
DOMAIN-KEYWORD,blogspot,Google 专用节点,force-remote-dns
# > Microsoft
DOMAIN-SUFFIX,onedrive.live.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,xboxlive.com,PROXY,force-remote-dns
# > Facebook
DOMAIN-SUFFIX,cdninstagram.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,fb.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,fb.me,PROXY,force-remote-dns
DOMAIN-SUFFIX,fbaddins.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,fbcdn.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,fbsbx.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,fbworkmail.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,instagram.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,m.me,PROXY,force-remote-dns
DOMAIN-SUFFIX,messenger.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,oculus.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,oculuscdn.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,rocksdb.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,whatsapp.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,whatsapp.net,PROXY,force-remote-dns
DOMAIN-KEYWORD,facebook,PROXY,force-remote-dns
IP-CIDR,3.123.36.126/32,PROXY,no-resolve
IP-CIDR,35.157.215.84/32,PROXY,no-resolve
IP-CIDR,35.157.217.255/32,PROXY,no-resolve
IP-CIDR,52.58.209.134/32,PROXY,no-resolve
IP-CIDR,54.93.124.31/32,PROXY,no-resolve
IP-CIDR,54.162.243.80/32,PROXY,no-resolve
IP-CIDR,54.173.34.141/32,PROXY,no-resolve
IP-CIDR,54.235.23.242/32,PROXY,no-resolve
IP-CIDR,169.45.248.118/32,PROXY,no-resolve
# > Twitter
DOMAIN-SUFFIX,pscp.tv,PROXY,force-remote-dns
DOMAIN-SUFFIX,periscope.tv,PROXY,force-remote-dns
DOMAIN-SUFFIX,t.co,PROXY,force-remote-dns
DOMAIN-SUFFIX,twimg.co,PROXY,force-remote-dns
DOMAIN-SUFFIX,twimg.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,twitpic.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,vine.co,PROXY,force-remote-dns
DOMAIN-KEYWORD,twitter,PROXY,force-remote-dns
# > Telegram
DOMAIN-SUFFIX,t.me,Telegram 专用节点
DOMAIN-SUFFIX,tdesktop.com,Telegram 专用节点
DOMAIN-SUFFIX,telegra.ph,Telegram 专用节点,force-remote-dns
DOMAIN-SUFFIX,telegram.me,Telegram 专用节点
DOMAIN-SUFFIX,telegram.org,Telegram 专用节点,force-remote-dns
IP-CIDR,91.108.4.0/22,Telegram 专用节点,no-resolve
IP-CIDR,91.108.8.0/22,Telegram 专用节点,no-resolve
IP-CIDR,91.108.12.0/22,Telegram 专用节点,no-resolve
IP-CIDR,91.108.16.0/22,Telegram 专用节点,no-resolve
IP-CIDR,91.108.56.0/22,Telegram 专用节点,no-resolve
IP-CIDR,149.154.160.0/20,Telegram 专用节点,no-resolve
# > Line
DOMAIN-SUFFIX,line.me,PROXY,force-remote-dns
DOMAIN-SUFFIX,line-apps.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,line-scdn.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,naver.jp,PROXY,force-remote-dns
IP-CIDR,103.2.30.0/23,PROXY,no-resolve
IP-CIDR,125.209.208.0/20,PROXY,no-resolve
IP-CIDR,147.92.128.0/17,PROXY,no-resolve
IP-CIDR,203.104.144.0/21,PROXY,no-resolve
# > Other
DOMAIN-SUFFIX,4shared.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,520cc.cc,PROXY,force-remote-dns
DOMAIN-SUFFIX,881903.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,9cache.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,9gag.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,abc.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,abc.net.au,PROXY,force-remote-dns
DOMAIN-SUFFIX,abebooks.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,amazon.co.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,apigee.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,apk-dl.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,apkfind.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,apkmirror.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,apkmonk.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,apkpure.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,aptoide.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,archive.is,PROXY,force-remote-dns
DOMAIN-SUFFIX,archive.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,arte.tv,PROXY,force-remote-dns
DOMAIN-SUFFIX,artstation.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,arukas.io,PROXY,force-remote-dns
DOMAIN-SUFFIX,ask.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,avg.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,avgle.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,badoo.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,bandwagonhost.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,bbc.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,behance.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,bibox.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,biggo.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,binance.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,bitcointalk.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,bitfinex.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,bitmex.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,bit-z.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,bloglovin.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,bloomberg.cn,PROXY,force-remote-dns
DOMAIN-SUFFIX,bloomberg.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,blubrry.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,book.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,booklive.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,books.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,boslife.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,box.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,businessinsider.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,bwh1.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,castbox.fm,PROXY,force-remote-dns
DOMAIN-SUFFIX,cbc.ca,PROXY,force-remote-dns
DOMAIN-SUFFIX,cdw.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,change.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,channelnewsasia.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,ck101.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,clarionproject.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,clyp.it,PROXY,force-remote-dns
DOMAIN-SUFFIX,cna.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,comparitech.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,conoha.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,crucial.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,cts.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,cw.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,cyberctm.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dailymotion.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dailyview.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,daum.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,daumcdn.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,dcard.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,deepdiscount.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,depositphotos.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,deviantart.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,disconnect.me,PROXY,force-remote-dns
DOMAIN-SUFFIX,discordapp.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,discordapp.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,disqus.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dlercloud.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dns2go.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dowjones.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dropbox.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dropboxusercontent.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,duckduckgo.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dw.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,dynu.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,earthcam.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,ebookservice.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,economist.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,edgecastcdn.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,edu,PROXY,force-remote-dns
DOMAIN-SUFFIX,elpais.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,enanyang.my,PROXY,force-remote-dns
DOMAIN-SUFFIX,encyclopedia.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,esoir.be,PROXY,force-remote-dns
DOMAIN-SUFFIX,etherscan.io,PROXY,force-remote-dns
DOMAIN-SUFFIX,euronews.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,evozi.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,feedly.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,firech.at,PROXY,force-remote-dns
DOMAIN-SUFFIX,flickr.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,flitto.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,foreignpolicy.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,freebrowser.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,freewechat.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,freeweibo.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,friday.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,ftchinese.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,ftimg.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,gate.io,PROXY,force-remote-dns
DOMAIN-SUFFIX,getlantern.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,getsync.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,globalvoices.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,goo.ne.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,goodreads.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,gov,PROXY,force-remote-dns
DOMAIN-SUFFIX,gov.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,greatfire.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,gumroad.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hbg.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,heroku.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hightail.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hk01.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hkbf.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,hkbookcity.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hkej.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hket.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hkgolden.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hootsuite.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,hudson.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,hyread.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,ibtimes.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,i-cable.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,icij.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,icoco.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,imgur.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,initiummall.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,insecam.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,ipfs.io,PROXY,force-remote-dns
DOMAIN-SUFFIX,issuu.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,istockphoto.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,japantimes.co.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,jiji.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,jinx.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,jkforum.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,joinmastodon.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,justmysocks.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,justpaste.it,PROXY,force-remote-dns
DOMAIN-SUFFIX,kakao.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,kakaocorp.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,kik.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,kobo.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,kobobooks.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,kodingen.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,lemonde.fr,PROXY,force-remote-dns
DOMAIN-SUFFIX,lepoint.fr,PROXY,force-remote-dns
DOMAIN-SUFFIX,lihkg.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,listennotes.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,livestream.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,logmein.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,mail.ru,PROXY,force-remote-dns
DOMAIN-SUFFIX,mailchimp.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,marc.info,PROXY,force-remote-dns
DOMAIN-SUFFIX,matters.news,PROXY,force-remote-dns
DOMAIN-SUFFIX,maying.co,PROXY,force-remote-dns
DOMAIN-SUFFIX,medium.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,mega.nz,PROXY,force-remote-dns
DOMAIN-SUFFIX,mil,PROXY,force-remote-dns
DOMAIN-SUFFIX,mingpao.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,mobile01.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,myspace.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,myspacecdn.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nanyang.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,naver.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,neowin.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,newstapa.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,nexitally.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nhk.or.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,nicovideo.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,nii.ac.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,nikkei.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nofile.io,PROXY,force-remote-dns
DOMAIN-SUFFIX,now.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nrk.no,PROXY,force-remote-dns
DOMAIN-SUFFIX,nyt.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nytchina.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nytcn.me,PROXY,force-remote-dns
DOMAIN-SUFFIX,nytco.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nytimes.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nytimg.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nytlog.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,nytstyle.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,ok.ru,PROXY,force-remote-dns
DOMAIN-SUFFIX,okex.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,on.cc,PROXY,force-remote-dns
DOMAIN-SUFFIX,orientaldaily.com.my,PROXY,force-remote-dns
DOMAIN-SUFFIX,overcast.fm,PROXY,force-remote-dns
DOMAIN-SUFFIX,paltalk.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,pao-pao.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,parsevideo.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,pbxes.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,pcdvd.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,pchome.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,pcloud.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,picacomic.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,pinimg.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,pixiv.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,player.fm,PROXY,force-remote-dns
DOMAIN-SUFFIX,plurk.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,po18.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,potato.im,PROXY,force-remote-dns
DOMAIN-SUFFIX,potatso.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,prism-break.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,proxifier.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,pt.im,PROXY,force-remote-dns
DOMAIN-SUFFIX,pts.org.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,pubu.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,pubu.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,pureapk.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,quora.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,quoracdn.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,rakuten.co.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,readingtimes.com.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,readmoo.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,redbubble.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,reddit.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,redditmedia.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,resilio.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,reuters.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,reutersmedia.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,rfi.fr,PROXY,force-remote-dns
DOMAIN-SUFFIX,rixcloud.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,roadshow.hk,PROXY,force-remote-dns
DOMAIN-SUFFIX,scmp.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,scribd.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,seatguru.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,shadowsocks.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,shopee.tw,PROXY,force-remote-dns
DOMAIN-SUFFIX,slideshare.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,softfamous.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,ssrcloud.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,startpage.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,steamcommunity.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,steemit.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,steemitwallet.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,t66y.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,tapatalk.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,teco-hk.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,teco-mo.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,teddysun.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,textnow.me,PROXY,force-remote-dns
DOMAIN-SUFFIX,theguardian.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,theinitium.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,thetvdb.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,tineye.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,torproject.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,tumblr.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,turbobit.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,tutanota.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,tvboxnow.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,udn.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,unseen.is,PROXY,force-remote-dns
DOMAIN-SUFFIX,upmedia.mg,PROXY,force-remote-dns
DOMAIN-SUFFIX,uptodown.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,urbandictionary.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,ustream.tv,PROXY,force-remote-dns
DOMAIN-SUFFIX,uwants.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,v2ray.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,viber.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,videopress.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,vimeo.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,voachinese.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,voanews.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,voxer.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,vzw.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,w3schools.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,washingtonpost.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,wattpad.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,whoer.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,wikimapia.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,wikipedia.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,wikiquote.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,wikiwand.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,winudf.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,wire.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,wordpress.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,workflow.is,PROXY,force-remote-dns
DOMAIN-SUFFIX,worldcat.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,wsj.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,wsj.net,PROXY,force-remote-dns
DOMAIN-SUFFIX,xhamster.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,xn--90wwvt03e.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,xn--i2ru8q2qg.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,xnxx.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,xvideos.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,yahoo.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,yandex.ru,PROXY,force-remote-dns
DOMAIN-SUFFIX,ycombinator.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,yesasia.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,yes-news.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,yomiuri.co.jp,PROXY,force-remote-dns
DOMAIN-SUFFIX,you-get.org,PROXY,force-remote-dns
DOMAIN-SUFFIX,zaobao.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,zb.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,zello.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,zeronet.io,PROXY,force-remote-dns
DOMAIN-SUFFIX,zoom.us,PROXY,force-remote-dns
DOMAIN-KEYWORD,github,PROXY,force-remote-dns
DOMAIN-KEYWORD,jav,PROXY,force-remote-dns
DOMAIN-KEYWORD,pinterest,PROXY,force-remote-dns
DOMAIN-KEYWORD,porn,PROXY,force-remote-dns
DOMAIN-KEYWORD,wikileaks,PROXY,force-remote-dns

# (Region-Restricted Access Denied)
DOMAIN-SUFFIX,apartmentratings.com,PROXY
DOMAIN-SUFFIX,apartments.com,PROXY
DOMAIN-SUFFIX,bankmobilevibe.com,PROXY
DOMAIN-SUFFIX,bing.com,PROXY,force-remote-dns
DOMAIN-SUFFIX,booktopia.com.au,PROXY
DOMAIN-SUFFIX,cccat.io,PROXY
DOMAIN-SUFFIX,centauro.com.br,PROXY
DOMAIN-SUFFIX,clearsurance.com,PROXY
DOMAIN-SUFFIX,costco.com,PROXY
DOMAIN-SUFFIX,crackle.com,PROXY
DOMAIN-SUFFIX,depositphotos.cn,PROXY
DOMAIN-SUFFIX,dish.com,PROXY
DOMAIN-SUFFIX,dmm.co.jp,PROXY
DOMAIN-SUFFIX,dmm.com,PROXY
DOMAIN-SUFFIX,dnvod.tv,PROXY
DOMAIN-SUFFIX,esurance.com,PROXY
DOMAIN-SUFFIX,extmatrix.com,PROXY
DOMAIN-SUFFIX,fastpic.ru,PROXY
DOMAIN-SUFFIX,flipboard.com,PROXY
DOMAIN-SUFFIX,fnac.be,PROXY
DOMAIN-SUFFIX,fnac.com,PROXY
DOMAIN-SUFFIX,funkyimg.com,PROXY
DOMAIN-SUFFIX,fxnetworks.com,PROXY
DOMAIN-SUFFIX,gettyimages.com,PROXY
DOMAIN-SUFFIX,go.com,PROXY
DOMAIN-SUFFIX,here.com,PROXY
DOMAIN-SUFFIX,jcpenney.com,PROXY
DOMAIN-SUFFIX,jiehua.tv,PROXY
DOMAIN-SUFFIX,mailfence.com,PROXY
DOMAIN-SUFFIX,nationwide.com,PROXY
DOMAIN-SUFFIX,nbc.com,PROXY
DOMAIN-SUFFIX,nexon.com,PROXY
DOMAIN-SUFFIX,nordstrom.com,PROXY
DOMAIN-SUFFIX,nordstromimage.com,PROXY
DOMAIN-SUFFIX,nordstromrack.com,PROXY
DOMAIN-SUFFIX,superpages.com,PROXY
DOMAIN-SUFFIX,target.com,PROXY
DOMAIN-SUFFIX,thinkgeek.com,PROXY
DOMAIN-SUFFIX,tracfone.com,PROXY
DOMAIN-SUFFIX,unity3d.com,PROXY
DOMAIN-SUFFIX,uploader.jp,PROXY
DOMAIN-SUFFIX,vevo.com,PROXY
DOMAIN-SUFFIX,viu.tv,PROXY
DOMAIN-SUFFIX,vk.com,PROXY
DOMAIN-SUFFIX,vsco.co,PROXY
DOMAIN-SUFFIX,xfinity.com,PROXY
DOMAIN-SUFFIX,zattoo.com,PROXY
USER-AGENT,Roam*,PROXY

# (The Most Popular Sites)
# > Apple
# >> TestFlight
DOMAIN,testflight.apple.com,PROXY
# >> Apple URL Shortener
DOMAIN-SUFFIX,appsto.re,PROXY
# >> iBooks Store download
DOMAIN,books.itunes.apple.com,PROXY
# >> iTunes Store Moveis Trailers
DOMAIN,hls.itunes.apple.com,PROXY
# >> Spotlight
DOMAIN,api-glb-sea.smoot.apple.com,PROXY
# >> Dictionary
DOMAIN,lookup-api.apple.com,PROXY
# >> Apple News and Apple Map TOMTOM Version
DOMAIN,gspe1-ssl.ls.apple.com,⚠️不使用 AppleNews 选 DIRECT
USER-AGENT,AppleNews*,PROXY
USER-AGENT,com.apple.news*,PROXY
DOMAIN-SUFFIX,apple.news,PROXY
DOMAIN,news-client.apple.com,PROXY
DOMAIN,news-edge.apple.com,PROXY
DOMAIN,news-events.apple.com,PROXY
DOMAIN,apple.comscoreresearch.com,PROXY
# > Google
DOMAIN-SUFFIX,abc.xyz,PROXY
DOMAIN-SUFFIX,android.com,PROXY
DOMAIN-SUFFIX,androidify.com,PROXY
DOMAIN-SUFFIX,dialogflow.com,PROXY
DOMAIN-SUFFIX,autodraw.com,PROXY
DOMAIN-SUFFIX,capitalg.com,PROXY
DOMAIN-SUFFIX,certificate-transparency.org,PROXY
DOMAIN-SUFFIX,chrome.com,PROXY
DOMAIN-SUFFIX,chromeexperiments.com,PROXY
DOMAIN-SUFFIX,chromestatus.com,PROXY
DOMAIN-SUFFIX,chromium.org,PROXY
DOMAIN-SUFFIX,creativelab5.com,PROXY
DOMAIN-SUFFIX,debug.com,PROXY
DOMAIN-SUFFIX,deepmind.com,PROXY
DOMAIN-SUFFIX,firebaseio.com,PROXY
DOMAIN-SUFFIX,getmdl.io,PROXY
DOMAIN-SUFFIX,ggpht.com,PROXY
DOMAIN-SUFFIX,gmail.com,PROXY
DOMAIN-SUFFIX,gmodules.com,PROXY
DOMAIN-SUFFIX,godoc.org,PROXY
DOMAIN-SUFFIX,golang.org,PROXY
DOMAIN-SUFFIX,gstatic.com,PROXY
DOMAIN-SUFFIX,gv.com,PROXY
DOMAIN-SUFFIX,gwtproject.org,PROXY
DOMAIN-SUFFIX,itasoftware.com,PROXY
DOMAIN-SUFFIX,madewithcode.com,PROXY
DOMAIN-SUFFIX,material.io,PROXY
DOMAIN-SUFFIX,polymer-project.org,PROXY
DOMAIN-SUFFIX,admin.recaptcha.net,PROXY
DOMAIN-SUFFIX,recaptcha.net,PROXY
DOMAIN-SUFFIX,shattered.io,PROXY
DOMAIN-SUFFIX,synergyse.com,PROXY
DOMAIN-SUFFIX,tensorflow.org,PROXY
DOMAIN-SUFFIX,tfhub.dev,PROXY
DOMAIN-SUFFIX,tiltbrush.com,PROXY
DOMAIN-SUFFIX,waveprotocol.org,PROXY
DOMAIN-SUFFIX,waymo.com,PROXY
DOMAIN-SUFFIX,webmproject.org,PROXY
DOMAIN-SUFFIX,webrtc.org,PROXY
DOMAIN-SUFFIX,whatbrowser.org,PROXY
DOMAIN-SUFFIX,widevine.com,PROXY
DOMAIN-SUFFIX,x.company,PROXY
DOMAIN-SUFFIX,youtu.be,PROXY
DOMAIN-SUFFIX,yt.be,PROXY
DOMAIN-SUFFIX,ytimg.com,PROXY
# > Microsoft
# >> Microsoft OneDrive
DOMAIN-SUFFIX,1drv.com,PROXY
DOMAIN-SUFFIX,1drv.ms,PROXY
DOMAIN-SUFFIX,blob.core.windows.net,PROXY
DOMAIN-SUFFIX,livefilestore.com,PROXY
DOMAIN-SUFFIX,onedrive.com,PROXY
DOMAIN-SUFFIX,storage.live.com,PROXY
DOMAIN-SUFFIX,storage.msn.com,PROXY
DOMAIN,oneclient.sfx.ms,PROXY
# > Other
DOMAIN-SUFFIX,0rz.tw,PROXY
DOMAIN-SUFFIX,4bluestones.biz,PROXY
DOMAIN-SUFFIX,9bis.net,PROXY
DOMAIN-SUFFIX,allconnected.co,PROXY
DOMAIN-SUFFIX,aol.com,PROXY
DOMAIN-SUFFIX,bcc.com.tw,PROXY
DOMAIN-SUFFIX,bit.ly,PROXY
DOMAIN-SUFFIX,bitshare.com,PROXY
DOMAIN-SUFFIX,blog.jp,PROXY
DOMAIN-SUFFIX,blogimg.jp,PROXY
DOMAIN-SUFFIX,blogtd.org,PROXY
DOMAIN-SUFFIX,broadcast.co.nz,PROXY
DOMAIN-SUFFIX,camfrog.com,PROXY
DOMAIN-SUFFIX,cfos.de,PROXY
DOMAIN-SUFFIX,citypopulation.de,PROXY
DOMAIN-SUFFIX,cloudfront.net,PROXY
DOMAIN-SUFFIX,ctitv.com.tw,PROXY
DOMAIN-SUFFIX,cuhk.edu.hk,PROXY
DOMAIN-SUFFIX,cusu.hk,PROXY
DOMAIN-SUFFIX,discord.gg,PROXY
DOMAIN-SUFFIX,discuss.com.hk,PROXY
DOMAIN-SUFFIX,dropboxapi.com,PROXY
DOMAIN-SUFFIX,duolingo.cn,PROXY
DOMAIN-SUFFIX,edditstatic.com,PROXY
DOMAIN-SUFFIX,flickriver.com,PROXY
DOMAIN-SUFFIX,focustaiwan.tw,PROXY
DOMAIN-SUFFIX,free.fr,PROXY
DOMAIN-SUFFIX,gigacircle.com,PROXY
DOMAIN-SUFFIX,hk-pub.com,PROXY
DOMAIN-SUFFIX,hosting.co.uk,PROXY
DOMAIN-SUFFIX,hwcdn.net,PROXY
DOMAIN-SUFFIX,ifixit.com,PROXY
DOMAIN-SUFFIX,iphone4hongkong.com,PROXY
DOMAIN-SUFFIX,iphonetaiwan.org,PROXY
DOMAIN-SUFFIX,iptvbin.com,PROXY
DOMAIN-SUFFIX,linksalpha.com,PROXY
DOMAIN-SUFFIX,manyvids.com,PROXY
DOMAIN-SUFFIX,myactimes.com,PROXY
DOMAIN-SUFFIX,newsblur.com,PROXY
DOMAIN-SUFFIX,now.im,PROXY
DOMAIN-SUFFIX,redditlist.com,PROXY
DOMAIN-SUFFIX,s3.amazonaws.com,PROXY
DOMAIN-SUFFIX,signal.org,PROXY
DOMAIN-SUFFIX,smartmailcloud.com,PROXY
DOMAIN-SUFFIX,sparknotes.com,PROXY
DOMAIN-SUFFIX,streetvoice.com,PROXY
DOMAIN-SUFFIX,supertop.co,PROXY
DOMAIN-SUFFIX,tv.com,PROXY
DOMAIN-SUFFIX,typepad.com,PROXY
DOMAIN-SUFFIX,udnbkk.com,PROXY
DOMAIN-SUFFIX,urbanairship.com,PROXY
DOMAIN-SUFFIX,whispersystems.org,PROXY
DOMAIN-SUFFIX,wikia.com,PROXY
DOMAIN-SUFFIX,wn.com,PROXY
DOMAIN-SUFFIX,wolframalpha.com,PROXY
DOMAIN-SUFFIX,x-art.com,PROXY
DOMAIN-SUFFIX,yimg.com,PROXY
DOMAIN,api.steampowered.com,PROXY
DOMAIN,store.steampowered.com,PROXY

# China Area Network
# > 360
DOMAIN-SUFFIX,qhres.com,DIRECT
DOMAIN-SUFFIX,qhimg.com,DIRECT
# > Akamai
DOMAIN-SUFFIX,akadns.net,DIRECT
# DOMAIN-SUFFIX,akamai.net,DIRECT
# DOMAIN-SUFFIX,akamaiedge.net,DIRECT
# DOMAIN-SUFFIX,akamaihd.net,DIRECT
# DOMAIN-SUFFIX,akamaistream.net,DIRECT
# DOMAIN-SUFFIX,akamaized.net,DIRECT
# > Alibaba
USER-AGENT,%E4%BC%98%E9%85%B7*,DIRECT
DOMAIN-SUFFIX,alibaba.com,DIRECT
DOMAIN-SUFFIX,alicdn.com,DIRECT
DOMAIN-SUFFIX,alikunlun.com,DIRECT
DOMAIN-SUFFIX,alipay.com,DIRECT
DOMAIN-SUFFIX,amap.com,DIRECT
DOMAIN-SUFFIX,autonavi.com,DIRECT
DOMAIN-SUFFIX,dingtalk.com,DIRECT
DOMAIN-SUFFIX,mxhichina.com,DIRECT
DOMAIN-SUFFIX,soku.com,DIRECT
DOMAIN-SUFFIX,taobao.com,DIRECT
DOMAIN-SUFFIX,tmall.com,DIRECT
DOMAIN-SUFFIX,tmall.hk,DIRECT
DOMAIN-SUFFIX,ykimg.com,DIRECT
DOMAIN-SUFFIX,youku.com,DIRECT
DOMAIN-SUFFIX,xiami.com,DIRECT
DOMAIN-SUFFIX,xiami.net,DIRECT
# > Apple
DOMAIN-SUFFIX,aaplimg.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,apple.co,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,apple.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,apple-cloudkit.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,appstore.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,cdn-apple.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,crashlytics.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,icloud.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,icloud-content.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,me.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN-SUFFIX,mzstatic.com,⚠️Apple 服务代理(不明白就选DIRECT)
DOMAIN,www-cdn.icloud.com.akadns.net,⚠️Apple 服务代理(不明白就选DIRECT)
IP-CIDR,17.0.0.0/8,⚠️Apple 服务代理(不明白就选DIRECT)
# > Baidu
DOMAIN-SUFFIX,baidu.com,DIRECT
DOMAIN-SUFFIX,baidubcr.com,DIRECT
DOMAIN-SUFFIX,bdstatic.com,DIRECT
DOMAIN-SUFFIX,yunjiasu-cdn.net,DIRECT
# > bilibili
DOMAIN-SUFFIX,acgvideo.com,DIRECT
DOMAIN-SUFFIX,biliapi.com,DIRECT
DOMAIN-SUFFIX,biliapi.net,DIRECT
DOMAIN-SUFFIX,bilibili.com,DIRECT
DOMAIN-SUFFIX,bilibili.tv,DIRECT
DOMAIN-SUFFIX,hdslb.com,DIRECT
# > Blizzard
DOMAIN-SUFFIX,blizzard.com,DIRECT
DOMAIN-SUFFIX,battle.net,DIRECT
DOMAIN,blzddist1-a.akamaihd.net,DIRECT
# > ByteDance
DOMAIN-SUFFIX,feiliao.com,DIRECT
DOMAIN-SUFFIX,pstatp.com,DIRECT
DOMAIN-SUFFIX,snssdk.com,DIRECT
DOMAIN-SUFFIX,iesdouyin.com,DIRECT
DOMAIN-SUFFIX,toutiao.com,DIRECT
# > CCTV
DOMAIN-SUFFIX,cctv.com,DIRECT
DOMAIN-SUFFIX,cctvpic.com,DIRECT
DOMAIN-SUFFIX,livechina.com,DIRECT
# > DiDi
DOMAIN-SUFFIX,didialift.com,DIRECT
DOMAIN-SUFFIX,didiglobal.com,DIRECT
DOMAIN-SUFFIX,udache.com,DIRECT
# > 蛋蛋赞
DOMAIN-SUFFIX,343480.com,DIRECT
DOMAIN-SUFFIX,baduziyuan.com,DIRECT
DOMAIN-SUFFIX,com-hs-hkdy.com,DIRECT
DOMAIN-SUFFIX,czybjz.com,DIRECT
DOMAIN-SUFFIX,dandanzan.com,DIRECT
DOMAIN-SUFFIX,fjhps.com,DIRECT
DOMAIN-SUFFIX,kuyunbo.club,DIRECT
# > ChinaNet
DOMAIN-SUFFIX,21cn.com,DIRECT
# > HunanTV
DOMAIN-SUFFIX,hitv.com,DIRECT
DOMAIN-SUFFIX,mgtv.com,DIRECT
# > iQiyi
DOMAIN-SUFFIX,iqiyi.com,DIRECT
DOMAIN-SUFFIX,iqiyipic.com,DIRECT
DOMAIN-SUFFIX,71.am.com,DIRECT
# > JD
DOMAIN-SUFFIX,jd.com,DIRECT
DOMAIN-SUFFIX,jd.hk,DIRECT
DOMAIN-SUFFIX,jdpay.com,DIRECT
DOMAIN-SUFFIX,360buyimg.com,DIRECT
# > Kingsoft
DOMAIN-SUFFIX,iciba.com,DIRECT
DOMAIN-SUFFIX,ksosoft.com,DIRECT
# > Meitu
DOMAIN-SUFFIX,meitu.com,DIRECT
DOMAIN-SUFFIX,meitudata.com,DIRECT
DOMAIN-SUFFIX,meitustat.com,DIRECT
DOMAIN-SUFFIX,meipai.com,DIRECT
# > MI
DOMAIN-SUFFIX,duokan.com,DIRECT
DOMAIN-SUFFIX,mi-img.com,DIRECT
DOMAIN-SUFFIX,miui.com,DIRECT
DOMAIN-SUFFIX,miwifi.com,DIRECT
DOMAIN-SUFFIX,xiaomi.com,DIRECT
# > Microsoft
DOMAIN-SUFFIX,microsoft.com,DIRECT
DOMAIN-SUFFIX,msecnd.net,DIRECT
DOMAIN-SUFFIX,office365.com,DIRECT
DOMAIN-SUFFIX,outlook.com,DIRECT
DOMAIN-SUFFIX,s-microsoft.com,DIRECT
DOMAIN-SUFFIX,visualstudio.com,DIRECT
DOMAIN-SUFFIX,windows.com,DIRECT
DOMAIN-SUFFIX,windowsupdate.com,DIRECT
DOMAIN,officecdn-microsoft-com.akamaized.net,DIRECT
# > NetEase
USER-AGENT,NeteaseMusic*,DIRECT
USER-AGENT,%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90*,DIRECT
DOMAIN-SUFFIX,163.com,DIRECT
DOMAIN-SUFFIX,126.net,DIRECT
DOMAIN-SUFFIX,127.net,DIRECT
DOMAIN-SUFFIX,163yun.com,DIRECT
DOMAIN-SUFFIX,lofter.com,DIRECT
DOMAIN-SUFFIX,netease.com,DIRECT
DOMAIN-SUFFIX,ydstatic.com,DIRECT
# > Sina
DOMAIN-SUFFIX,sina.com,DIRECT
DOMAIN-SUFFIX,weibo.com,DIRECT
DOMAIN-SUFFIX,weibocdn.com,DIRECT
# > Sohu
DOMAIN-SUFFIX,sohu.com,DIRECT
DOMAIN-SUFFIX,sohucs.com,DIRECT
DOMAIN-SUFFIX,sohu-inc.com,DIRECT
DOMAIN-SUFFIX,v-56.com,DIRECT
# > Sogo
DOMAIN-SUFFIX,sogo.com,DIRECT
DOMAIN-SUFFIX,sogou.com,DIRECT
DOMAIN-SUFFIX,sogoucdn.com,DIRECT
# > Steam
DOMAIN-SUFFIX,steampowered.com,DIRECT
DOMAIN-SUFFIX,steam-chat.com,DIRECT
DOMAIN-SUFFIX,steamgames.com,DIRECT
DOMAIN-SUFFIX,steamusercontent.com,DIRECT
DOMAIN-SUFFIX,steamcontent.com,DIRECT
DOMAIN-SUFFIX,steamstatic.com,DIRECT
DOMAIN-SUFFIX,steamcdn-a.akamaihd.net,DIRECT
DOMAIN-SUFFIX,steamstat.us,DIRECT
# > Tencent
USER-AGENT,MicroMessenger%20Client,DIRECT
USER-AGENT,WeChat*,DIRECT
DOMAIN-SUFFIX,gtimg.com,DIRECT
DOMAIN-SUFFIX,idqqimg.com,DIRECT
DOMAIN-SUFFIX,igamecj.com,DIRECT
DOMAIN-SUFFIX,myapp.com,DIRECT
DOMAIN-SUFFIX,myqcloud.com,DIRECT
DOMAIN-SUFFIX,qq.com,DIRECT
DOMAIN-SUFFIX,tencent.com,DIRECT
DOMAIN-SUFFIX,tencent-cloud.net,DIRECT
# > YYeTs
USER-AGENT,YYeTs*,DIRECT
DOMAIN-SUFFIX,jstucdn.com,DIRECT
DOMAIN-SUFFIX,zimuzu.io,DIRECT
DOMAIN-SUFFIX,zimuzu.tv,DIRECT
DOMAIN-SUFFIX,zmz2019.com,DIRECT
DOMAIN-SUFFIX,zmzapi.com,DIRECT
DOMAIN-SUFFIX,zmzapi.net,DIRECT
DOMAIN-SUFFIX,zmzfile.com,DIRECT
# > Content Delivery Network
DOMAIN-SUFFIX,ccgslb.com,DIRECT
DOMAIN-SUFFIX,ccgslb.net,DIRECT
DOMAIN-SUFFIX,chinanetcenter.com,DIRECT
DOMAIN-SUFFIX,meixincdn.com,DIRECT
DOMAIN-SUFFIX,ourdvs.com,DIRECT
DOMAIN-SUFFIX,staticdn.net,DIRECT
DOMAIN-SUFFIX,wangsu.com,DIRECT
# > IP Query
DOMAIN-SUFFIX,ipip.net,DIRECT
DOMAIN-SUFFIX,ip.la,DIRECT
DOMAIN-SUFFIX,ip-cdn.com,DIRECT
DOMAIN-SUFFIX,ipv6-test.com,DIRECT
DOMAIN-SUFFIX,test-ipv6.com,DIRECT
DOMAIN-SUFFIX,whatismyip.com,DIRECT
# > Speed Test
# DOMAIN-SUFFIX,speedtest.net,DIRECT
DOMAIN-SUFFIX,netspeedtestmaster.com,DIRECT
DOMAIN,speedtest.macpaw.com,DIRECT
# > Private Tracker
DOMAIN-SUFFIX,awesome-hd.me,DIRECT
DOMAIN-SUFFIX,broadcasthe.net,DIRECT
DOMAIN-SUFFIX,chdbits.co,DIRECT
DOMAIN-SUFFIX,classix-unlimited.co.uk,DIRECT
DOMAIN-SUFFIX,empornium.me,DIRECT
DOMAIN-SUFFIX,gazellegames.net,DIRECT
DOMAIN-SUFFIX,hdchina.org,DIRECT
DOMAIN-SUFFIX,hdsky.me,DIRECT
DOMAIN-SUFFIX,icetorrent.org,DIRECT
DOMAIN-SUFFIX,jpopsuki.eu,DIRECT
DOMAIN-SUFFIX,keepfrds.com,DIRECT
DOMAIN-SUFFIX,madsrevolution.net,DIRECT
DOMAIN-SUFFIX,m-team.cc,DIRECT
DOMAIN-SUFFIX,nanyangpt.com,DIRECT
DOMAIN-SUFFIX,ncore.cc,DIRECT
DOMAIN-SUFFIX,open.cd,DIRECT
DOMAIN-SUFFIX,ourbits.club,DIRECT
DOMAIN-SUFFIX,passthepopcorn.me,DIRECT
DOMAIN-SUFFIX,privatehd.to,DIRECT
DOMAIN-SUFFIX,redacted.ch,DIRECT
DOMAIN-SUFFIX,springsunday.net,DIRECT
DOMAIN-SUFFIX,tjupt.org,DIRECT
DOMAIN-SUFFIX,totheglory.im,DIRECT
# > Scholar
DOMAIN-SUFFIX,acm.org,DIRECT
DOMAIN-SUFFIX,acs.org,DIRECT
DOMAIN-SUFFIX,aip.org,DIRECT
DOMAIN-SUFFIX,ams.org,DIRECT
DOMAIN-SUFFIX,annualreviews.org,DIRECT
DOMAIN-SUFFIX,aps.org,DIRECT
DOMAIN-SUFFIX,ascelibrary.org,DIRECT
DOMAIN-SUFFIX,asm.org,DIRECT
DOMAIN-SUFFIX,asme.org,DIRECT
DOMAIN-SUFFIX,astm.org,DIRECT
DOMAIN-SUFFIX,bmj.com,DIRECT
DOMAIN-SUFFIX,cambridge.org,DIRECT
DOMAIN-SUFFIX,cas.org,DIRECT
DOMAIN-SUFFIX,clarivate.com,DIRECT
DOMAIN-SUFFIX,ebscohost.com,DIRECT
DOMAIN-SUFFIX,emerald.com,DIRECT
DOMAIN-SUFFIX,engineeringvillage.com,DIRECT
DOMAIN-SUFFIX,icevirtuallibrary.com,DIRECT
DOMAIN-SUFFIX,ieee.org,DIRECT
DOMAIN-SUFFIX,imf.org,DIRECT
DOMAIN-SUFFIX,iop.org,DIRECT
DOMAIN-SUFFIX,jamanetwork.com,DIRECT
DOMAIN-SUFFIX,jhu.edu,DIRECT
DOMAIN-SUFFIX,jstor.org,DIRECT
DOMAIN-SUFFIX,karger.com,DIRECT
DOMAIN-SUFFIX,libguides.com,DIRECT
DOMAIN-SUFFIX,madsrevolution.net,DIRECT
DOMAIN-SUFFIX,mpg.de,DIRECT
DOMAIN-SUFFIX,myilibrary.com,DIRECT
DOMAIN-SUFFIX,nature.com,DIRECT
DOMAIN-SUFFIX,oecd-ilibrary.org,DIRECT
DOMAIN-SUFFIX,osapublishing.org,DIRECT
DOMAIN-SUFFIX,oup.com,DIRECT
DOMAIN-SUFFIX,ovid.com,DIRECT
DOMAIN-SUFFIX,oxfordartonline.com,DIRECT
DOMAIN-SUFFIX,oxfordbibliographies.com,DIRECT
DOMAIN-SUFFIX,oxfordmusiconline.com,DIRECT
DOMAIN-SUFFIX,pnas.org,DIRECT
DOMAIN-SUFFIX,proquest.com,DIRECT
DOMAIN-SUFFIX,rsc.org,DIRECT
DOMAIN-SUFFIX,sagepub.com,DIRECT
DOMAIN-SUFFIX,sciencedirect.com,DIRECT
DOMAIN-SUFFIX,sciencemag.org,DIRECT
DOMAIN-SUFFIX,scopus.com,DIRECT
DOMAIN-SUFFIX,siam.org,DIRECT
DOMAIN-SUFFIX,spiedigitallibrary.org,DIRECT
DOMAIN-SUFFIX,springer.com,DIRECT
DOMAIN-SUFFIX,springerlink.com,DIRECT
DOMAIN-SUFFIX,tandfonline.com,DIRECT
DOMAIN-SUFFIX,un.org,DIRECT
DOMAIN-SUFFIX,uni-bielefeld.de,DIRECT
DOMAIN-SUFFIX,webofknowledge.com,DIRECT
DOMAIN-SUFFIX,westlaw.com,DIRECT
DOMAIN-SUFFIX,wiley.com,DIRECT
DOMAIN-SUFFIX,worldbank.org,DIRECT
DOMAIN-SUFFIX,worldscientific.com,DIRECT
# > Other
DOMAIN-SUFFIX,cn,DIRECT
DOMAIN-SUFFIX,360in.com,DIRECT
DOMAIN-SUFFIX,51ym.me,DIRECT
DOMAIN-SUFFIX,8686c.com,DIRECT
DOMAIN-SUFFIX,abchina.com,DIRECT
DOMAIN-SUFFIX,accuweather.com,DIRECT
DOMAIN-SUFFIX,aicoinstorge.com,DIRECT
DOMAIN-SUFFIX,air-matters.com,DIRECT
DOMAIN-SUFFIX,air-matters.io,DIRECT
DOMAIN-SUFFIX,aixifan.com,DIRECT
DOMAIN-SUFFIX,amd.com,DIRECT
DOMAIN-SUFFIX,b612.net,DIRECT
DOMAIN-SUFFIX,bdatu.com,DIRECT
DOMAIN-SUFFIX,beitaichufang.com,DIRECT
DOMAIN-SUFFIX,bjango.com,DIRECT
DOMAIN-SUFFIX,booking.com,DIRECT
DOMAIN-SUFFIX,bstatic.com,DIRECT
DOMAIN-SUFFIX,cailianpress.com,DIRECT
DOMAIN-SUFFIX,camera360.com,DIRECT
DOMAIN-SUFFIX,chinaso.com,DIRECT
DOMAIN-SUFFIX,chua.pro,DIRECT
DOMAIN-SUFFIX,chuimg.com,DIRECT
DOMAIN-SUFFIX,chunyu.mobi,DIRECT
DOMAIN-SUFFIX,chushou.tv,DIRECT
DOMAIN-SUFFIX,cmbchina.com,DIRECT
DOMAIN-SUFFIX,cmbimg.com,DIRECT
DOMAIN-SUFFIX,ctrip.com,DIRECT
DOMAIN-SUFFIX,dfcfw.com,DIRECT
DOMAIN-SUFFIX,docschina.org,DIRECT
DOMAIN-SUFFIX,douban.com,DIRECT
DOMAIN-SUFFIX,doubanio.com,DIRECT
DOMAIN-SUFFIX,douyu.com,DIRECT
DOMAIN-SUFFIX,dxycdn.com,DIRECT
DOMAIN-SUFFIX,dytt8.net,DIRECT
DOMAIN-SUFFIX,eastmoney.com,DIRECT
DOMAIN-SUFFIX,eudic.net,DIRECT
DOMAIN-SUFFIX,feng.com,DIRECT
DOMAIN-SUFFIX,fengkongcloud.com,DIRECT
DOMAIN-SUFFIX,frdic.com,DIRECT
DOMAIN-SUFFIX,futu5.com,DIRECT
DOMAIN-SUFFIX,futunn.com,DIRECT
DOMAIN-SUFFIX,gandi.net,DIRECT
DOMAIN-SUFFIX,geilicdn.com,DIRECT
DOMAIN-SUFFIX,getpricetag.com,DIRECT
DOMAIN-SUFFIX,gifshow.com,DIRECT
DOMAIN-SUFFIX,godic.net,DIRECT
DOMAIN-SUFFIX,hicloud.com,DIRECT
DOMAIN-SUFFIX,hongxiu.com,DIRECT
DOMAIN-SUFFIX,hostbuf.com,DIRECT
DOMAIN-SUFFIX,huxiucdn.com,DIRECT
DOMAIN-SUFFIX,huya.com,DIRECT
DOMAIN-SUFFIX,infinitynewtab.com,DIRECT
DOMAIN-SUFFIX,ithome.com,DIRECT
DOMAIN-SUFFIX,java.com,DIRECT
DOMAIN-SUFFIX,jidian.im,DIRECT
DOMAIN-SUFFIX,kaiyanapp.com,DIRECT
DOMAIN-SUFFIX,kaspersky-labs.com,DIRECT
DOMAIN-SUFFIX,keepcdn.com,DIRECT
DOMAIN-SUFFIX,kkmh.com,DIRECT
DOMAIN-SUFFIX,licdn.com,DIRECT
DOMAIN-SUFFIX,linkedin.com,DIRECT
DOMAIN-SUFFIX,loli.net,DIRECT
DOMAIN-SUFFIX,luojilab.com,DIRECT
DOMAIN-SUFFIX,maoyan.com,DIRECT
DOMAIN-SUFFIX,maoyun.tv,DIRECT
DOMAIN-SUFFIX,meituan.com,DIRECT
DOMAIN-SUFFIX,meituan.net,DIRECT
DOMAIN-SUFFIX,mobike.com,DIRECT
DOMAIN-SUFFIX,moke.com,DIRECT
DOMAIN-SUFFIX,mubu.com,DIRECT
DOMAIN-SUFFIX,myzaker.com,DIRECT
DOMAIN-SUFFIX,nim-lang-cn.org,DIRECT
DOMAIN-SUFFIX,nvidia.com,DIRECT
DOMAIN-SUFFIX,oracle.com,DIRECT
DOMAIN-SUFFIX,paypal.com,DIRECT
DOMAIN-SUFFIX,paypalobjects.com,DIRECT
DOMAIN-SUFFIX,qdaily.com,DIRECT
DOMAIN-SUFFIX,qidian.com,DIRECT
DOMAIN-SUFFIX,qyer.com,DIRECT
DOMAIN-SUFFIX,qyerstatic.com,DIRECT
DOMAIN-SUFFIX,raychase.net,DIRECT
DOMAIN-SUFFIX,ronghub.com,DIRECT
DOMAIN-SUFFIX,ruguoapp.com,DIRECT
DOMAIN-SUFFIX,s-reader.com,DIRECT
DOMAIN-SUFFIX,sankuai.com,DIRECT
DOMAIN-SUFFIX,scomper.me,DIRECT
DOMAIN-SUFFIX,seafile.com,DIRECT
DOMAIN-SUFFIX,sm.ms,DIRECT
DOMAIN-SUFFIX,smzdm.com,DIRECT
DOMAIN-SUFFIX,snapdrop.net,DIRECT
DOMAIN-SUFFIX,snwx.com,DIRECT
DOMAIN-SUFFIX,sspai.com,DIRECT
DOMAIN-SUFFIX,takungpao.com,DIRECT
DOMAIN-SUFFIX,teamviewer.com,DIRECT
DOMAIN-SUFFIX,tianyancha.com,DIRECT
DOMAIN-SUFFIX,udacity.com,DIRECT
DOMAIN-SUFFIX,uning.com,DIRECT
DOMAIN-SUFFIX,vmware.com,DIRECT
DOMAIN-SUFFIX,weather.com,DIRECT
DOMAIN-SUFFIX,weico.cc,DIRECT
DOMAIN-SUFFIX,weidian.com,DIRECT
DOMAIN-SUFFIX,xiachufang.com,DIRECT
DOMAIN-SUFFIX,ximalaya.com,DIRECT
DOMAIN-SUFFIX,xinhuanet.com,DIRECT
DOMAIN-SUFFIX,xmcdn.com,DIRECT
DOMAIN-SUFFIX,yangkeduo.com,DIRECT
DOMAIN-SUFFIX,zhangzishi.cc,DIRECT
DOMAIN-SUFFIX,zhihu.com,DIRECT
DOMAIN-SUFFIX,zhimg.com,DIRECT
DOMAIN-SUFFIX,zhuihd.com,DIRECT
DOMAIN,download.jetbrains.com,DIRECT
DOMAIN,images-cn.ssl-images-amazon.com,DIRECT
# > Exclusions
DOMAIN,translate.google.cn,PROXY

# (HKMTMedia)
# > bilibili
DOMAIN-SUFFIX,bilibili.com,⚠️bilibili港澳台专用节点(没有就选DIRECT)
DOMAIN,upos-hz-mirrorakam.akamaized.net,⚠️bilibili港澳台专用节点(没有就选DIRECT)
# > 愛奇藝台灣站
DOMAIN-SUFFIX,iqiyi.com,⚠️愛奇藝台灣站专用节点(没有就选DIRECT),force-remote-dns

# Local Area Network
DOMAIN-SUFFIX,local,DIRECT
IP-CIDR,192.168.0.0/16,DIRECT
IP-CIDR,10.0.0.0/8,DIRECT
IP-CIDR,172.16.0.0/12,DIRECT
IP-CIDR,127.0.0.0/8,DIRECT
IP-CIDR,100.64.0.0/10,DIRECT

# DNSPod Public DNS+
IP-CIDR,119.28.28.28/32,DIRECT,no-resolve
# GeoIP China
GEOIP,CN,DIRECT

FINAL,黑名单模式选 DIRECT 否则默认

[GLOBAL]
SELECTED,PROXY

[HOST]

[STATE]
STATE,AUTO

[MITM]
