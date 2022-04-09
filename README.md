Open kakao talk [LINK](https://open.kakao.com/o/gl8sklo)
# Zynq_TEST_PCB

Tool : kicad 6.0

  MAIN CHIP : XC7Z010-1CLG400C ([buy link](https://ko.aliexpress.com/item/4000052820744.html?gatewayAdapt=glo2kor&spm=a2g0o.order_list.0.0.21ef140fnMWK8L),  [metal mask buy link](https://ko.aliexpress.com/item/1005003821741873.html?gatewayAdapt=glo2kor&spm=a2g0o.order_list.0.0.21ef140fnMWK8L))

  DDR RAM CHIP : MT41K256M16HA-125( just usb form factor )
  
  
  
## Project step

### 1. make concept ( ~ 2022.04.05 )

      - 100Mbps ethernet
      - usb 2.0
      - ddr3 256MB 667Mhz
      - sd_card
      
### 2. drawing schematic ( ~ 2022.04.20 )

MAIN : XC7Z010-1CLG400C
POWER : ADP5052
JTAG : FT2232HQ
FLASH memory : 

4GB eMMC Flash
16MB QSPI Flash
TF card interface


DRAM : micron 4KK77-D9PTK
512MB DDR3 SDRAM (2 x 256MB, 32-bit)

DDR 고속 배선 아트웍 참조
https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=bestmind4276&logNo=220702125147

ethernet : RTL8211E
10/100/1000M Ethernet


usb host : USB3320C

아트웍 순서

1. DDR
2. EMMC
3. ETHERNET
4. USB
5. JTAG 
6. POWER



### 3. order pcb 

      - 4layer ( or 6layer )
      
### 4. hand Soldering

      - usb Metal Mask ( PCB Stencil )
      - HOT AIR FLOW GUN
      - FREE HEATTING BED
      
### 5. standard alone program test

### 6. linux poting
