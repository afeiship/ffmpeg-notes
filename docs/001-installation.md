# installation

## mac
```shell
# install from git
git clone git@github.com:FFmpeg/FFmpeg.git
cd FFmpeg
./configure
make && make install

# check if installed
ffmpeg -h
```


## problem
~~~
nasm/yasm not found or too old. Use --disable-x86asm for a crippled build.
~~~

```shell
brew install yasm
```

- https://blog.csdn.net/liuzehn/article/details/78667667
