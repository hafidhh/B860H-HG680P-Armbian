# B860H-HG680P-Armbian

## Buat Bootable  
Extract  
Buat bootable dengan bootable maker (balena etcher, ruful)  
Copy file dtb ke /dtb/armbian  

note : dtb sudah disesuaikan untuk RAM 2gb, untuk ram 1gb tidak perlu copu dtb

## Setting Armbian  
Setting WiFi, jam dll
Login Armbian -> input command
```yaml
armbian-config
```

## Maximize penggunaan SDcard atau Flashdisk  
Perinatah ini bertujuan untuk menggunakan seluruh kapasitas yang tersisa sebagai ROOT  
Login Armbian -> input command
```yaml
armbian-tf
```

## Docker
Login Armbian -> input command
```yaml
armbian-docker
```
  
  
Terimakasih untuk [ophub](https://github.com/ophub) yang telah menyediakan file iso armbian untuk amlogic s9xxx
