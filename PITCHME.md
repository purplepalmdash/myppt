# 云计算技术介绍

---

### 目录/Contents

- 云计算
- 虚拟化技术
- 容器与容器云
- 云端的大数据

---

### 什么是云计算
- 计算模型视角
这里是这里是
这里是这里是
这里是这里是
- 底层支撑技术视角
这里是这里是
这里是这里是
这里是这里是

- 服务提供视角
这里是这里是
这里是这里是
这里是这里是

---
### 一些源代码

```
// typical use : sudo ./a.out /dev/input/event*
int main (int argc, char *argv[])
{
  struct input_event ev[64];
  int fd[argc],rd,idev,value, size = sizeof (struct input_event);
  char name[256] = "Unknown";

  if(argc==1) return -1;

  int ndev=1;
  while(ndev<argc && (fd[ndev] = open (argv[ndev], O_RDONLY|O_NONBLOCK)) != -1){
    ndev++;
  }
  fprintf (stderr,"Found %i devices.\n", ndev);
  if(ndev==1) return -1;

```


---
