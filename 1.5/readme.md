## Задание 1

### describe.yaml 
- [describe.yaml](./01/describe.yaml)

### tail -f
![alt text](./01/image.png)

## Задание 2

### pv and pvc
![alt text](./02/image.png)

### check file
![alt text](./02/image-2.png)

```bash
# после удаления деплоя и pvc, pv не удаляется, потому что стоит retain в политике. Он переходит в состояние released.
```
### pv released
![alt text](./03/image-3.png)

### файл остался на ноде. При использовании hostpath он останется и после удаления PV.
![alt text](./03/image-1.png)

## Задание 3
![alt text](./03/image-4.png)