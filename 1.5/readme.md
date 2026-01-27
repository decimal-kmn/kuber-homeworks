## Задание 1

### describe.yaml 
- [describe.yaml](./01/describe.yaml)

### tail -f
![alt text](./01/image.png)

## Задание 2

### pv and pvc
![alt text](image.png)

### check file
![alt text](image-2.png)

```bash
# после удаления деплоя и pvc, pv не удаляется, потому что стоит retain в политике. Он переходит в состояние released.
```
### pv released
![alt text](image-3.png)

### файл остался на ноде. При использовании hostpath он останется и после удаления PV.
![alt text](image-1.png)

## Задание 3
![alt text](image-4.png)