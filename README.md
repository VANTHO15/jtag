## loadfile C:/thonv/gpio.bin 0x0 ( load file này vào và 0x0 là byte đầu tiên trong file.bin sẽ được load trong flash MCU)
## r : reset MCU
## g : go bắt đầu chạy 
## h : tạm dừng MCU

![image](https://user-images.githubusercontent.com/56969447/225380518-ee7496e6-0b46-4942-b364-0ff99c233456.png)
![image](https://user-images.githubusercontent.com/56969447/225383822-522c1f3f-2b77-465c-958a-be8ec92dee9e.png)
![image](https://user-images.githubusercontent.com/56969447/225383936-f007eb62-c0ab-447b-932b-73fb71791822.png)

Không dùng pin 5V

![image](https://github.com/VANTHO15/jtag/assets/56969447/acb3de1b-fcf9-48f1-9376-ba10307e09f4)
![image](https://github.com/VANTHO15/jtag/assets/56969447/7607e9ab-8437-426c-b119-bdbbbbc03a32)

# Connect Lauterbach
- Dùng SWD kết nối tới STM32F4 như bình thường
- Cấp thêm 1 nguồn ngoài là GND và 3.3V kết nối vào GND và pin 5V của STm32 là oke
![image](https://github.com/VANTHO15/jtag/assets/56969447/33602e7e-0367-4b40-92c9-b5aedf7abd20)
