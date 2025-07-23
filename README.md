# bash testing

слушать /dev/urandom
`ffmpeg -f u8 -ar 44100 -ac 2 -i /dev/urandom -af "afftfilt=real='hypot(re,im)*sin(0)':imag='hypot(re,im)*cos(0)':win_size=512:overlap=0.75" -f pulse "yup"`

`ffmpeg -f u8 -ar 44100 -ac 2 -i /dev/urandom -f pulse "asmr"`


![1](trolleybus-from-bread.jpg)
