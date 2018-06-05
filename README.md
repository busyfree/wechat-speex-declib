### wechat speex voice transfer

> convert speex to wav


#### Install speex

1. download speex source code, [http://p0d8hssbr.bkt.clouddn.com/softwares/speex-1.2.0.tar.gz](http://p0d8hssbr.bkt.clouddn.com/softwares/speex-1.2.0.tar.gz)

2. `tar xzvf speex-1.2.0.tar.gz`

3. `cd speex-1.2.0 && ./configure && make && make install`


#### Install decoder

1. `git clone https://github.com/gamelife1314/wechat-speex-declib.git`

2. `cd wechat-speex-declib && make && cp ./bin/speex_decode /usr/local/bin/speex2wav`

3. `speex2wav test.speex test.wav`