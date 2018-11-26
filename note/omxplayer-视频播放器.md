#### 参考：
    https://blog.csdn.net/sinat_31206523/article/details/78210363
    
#### 安装步骤：
    su - root
    apt-get install omxplayer

#### 图形界面：
    wget http://pexpect.sourceforge.net/pexpect-2.3.tar.gz
    tar xzf pexpect-2.3.tar.gz
    cd pexpect-2.3
    python ./setup.py install
    
    git clone https://github.com/KenT2/tboplayer.git
    cd tboplayer
    sh ./setup.sh
    
#### 视频播放使用：
    python tboplayer.py
    
#### 简易音频播放：
    for i in *;do omxplayer $i;done
    
    
#### 常用参数：
    omxplayer --help
    Usage: omxplayer [OPTIONS] [FILE]
    -h  --help                  Print this help
    -v  --version               Print version info
    -k  --keys                  Print key bindings
    -n  --aidx  index           Audio stream index    : e.g. 1
    -o  --adev  device          Audio out device      : e.g. hdmi/local/both
    -i  --info                  Dump stream format and exit
    -I  --with-info             dump stream format before playback
    -s  --stats                 Pts and buffer stats
    -p  --passthrough           Audio passthrough
    -d  --deinterlace           Force deinterlacing
        --nodeinterlace         Force no deinterlacing
        --nativedeinterlace     let display handle interlace
        --anaglyph type         convert 3d to anaglyph
        --advanced              Allow advanced deinterlace for HD videos
    -w  --hw                    Hw audio decoding
    -3  --3d mode               Switch tv into 3d mode (e.g. SBS/TB)
    -M  --allow-mvc             Allow decoding of both views of MVC stereo stream
    -y  --hdmiclocksync         Display refresh rate to match video (default)
    -z  --nohdmiclocksync       Do not adjust display refresh rate to match video
    -t  --sid index             Show subtitle with index
    -r  --refresh               Adjust framerate/resolution to video
    -g  --genlog                Generate log file
    -l  --pos n                 Start position (hh:mm:ss)
    -b  --blank                 Set background to black

#### 常用快捷键：
    z   Show Info  
    1   Decrease Speed
    2   Increase Speed
    j   Previous Audio stream
    k   Next Audio stream
    i   Previous Chapter
    o   Next Chapter
    n   Previous Subtitle stream
    m   Next Subtitle stream
    s   Toggle subtitles
    d   Subtitle delay -250ms
    f   Subtitle delay +250ms
    q   Exit Omxplayer
    -   Decrease Volume
    +   increase Volume
    Left Arrow  Seek -30s
    Right Arrow Seek +30s
    Down Arrow  Seek -600s
    Up Arrow    Seek +600s
    Space or p  Pasue/Resume



    
    
    
