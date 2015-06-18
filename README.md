“资源使用者”并发数变化很大的时候，这个实现并不高效。
比如现在并发为1，则只需要一个连接就可以，但该库依然会在cap个连接里轮询。


# pools
copy from vitess for making dependce less
