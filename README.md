# Traffic-identification-of-shadowsocks-based-on-convolutional-neural-network

Instructions：

```
from tensorflow.examples.tutorials.mnist import input_data 
# mnist.train.images  mnist.train.labels
# mnist.test.images  mnist.test.labels
mnist = input_data.read_data_sets(train_dir="XXXX", one_hot=False)
```

Label descrIption

```
ss_0123:
ss_aes-256-gcm  0
ss_aes-192-gcm  1
ss_aes-128-gcm  2
ss_rc4-md5      3

ss4_no:
normal          0
ss_aes-256-gcm  1
ss_aes-192-gcm  2
ss_aes-128-gcm  3
ss_rc4-md5      4

vpn_nonvpn:
normal          0
ss_aes-256-gcm  1
ss_aes-192-gcm  2
ss_aes-128-gcm  3
ss_rc4-md5      4
vpn             5


```

