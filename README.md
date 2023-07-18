# Opencore-efi-lenovo-m710q
The EFI installer for Lenovo Thinkcenter M710Q with Intel Sky Lake.

## Thông tin cấu hình máy gồm :
─ CPU
  └── Intel(R) Core(TM) i5-6500T CPU @ 2.50GHz
      ├── SSE: SSE4.2
      ├── SSSE3: Supported
      ├── Cores: 4
      └── Threads: 4

─ Motherboard
  ├── Model: 3111
  └── Vendor: LENOVO

─ GPU
  └── HD Graphics 530
      ├── Device ID: 0x1912
      ├── Vendor: 0x8086
      ├── ACPI Path: \_SB_.PCI0.GFX0
      └── PCI Path: PciRoot(0x0)/Pci(0x2,0x0)

─ Network
  ├── Wireless 8265 / 8275
  │   ├── Device ID: 0x24fd
  │   ├── Vendor: 0x8086
  │   ├── ACPI Path: \_SB_.PCI0.RP06.PXSX
  │   └── PCI Path: PciRoot(0x0)/Pci(0x1c,0x0)/Pci(0x0,0x0)
  └── Ethernet Connection (2) I219-V
      ├── Device ID: 0x15b8
      ├── Vendor: 0x8086
      ├── ACPI Path: \_SB_.PCI0.GLAN
      └── PCI Path: PciRoot(0x0)/Pci(0x1f,0x6)

─ Audio
  └── 200 Series PCH HD Audio
      ├── Device ID: 0xa2f0
      ├── Vendor: 0x8086
      ├── ACPI Path: \_SB_.PCI0.HDAS
      ├── PCI Path: PciRoot(0x0)/Pci(0x1f,0x3)
      └── Codec: ALC294

─ Storage
  ├──  IM2P33F3A NVMe ADATA 256GB
  │   ├── Type: Non-Volatile Memory Express (NVMe)
  │   ├── Connector: PCIe
  │   └── Location: Internal
  └── ATA GIGABYTE GP-GSTF
      ├── Type: Solid State Drive (SSD)
      ├── Connector: SCSI
      └── Location: Internal

*** Chú ý : Chỉ định cho người sử dụng adapter chuyển từ DG (from m710) sang HDMI (to Monitor) . Vã vẫn phải rút adapter mỗi lần reboot để trách lỗi Black Screen .

