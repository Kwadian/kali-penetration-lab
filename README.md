# Kali Linux ile Temel Sızma Testi

Bu projede Kali Linux üzerinde kurulu bir sızma testi laboratuvarı oluşturulmuş ve temel saldırı teknikleri test edilmiştir. Nmap, Wireshark ve diğer araçlarla ağ keşfi, zafiyet taramaları ve trafik analizi gerçekleştirilmiştir.

## Kullanılan Teknolojiler

- Kali Linux
- Nmap
- Wireshark
- VirtualBox / VMware (laboratuvar ortamı)
- Metasploitable (hedef makine)

## Yapılan İşlemler

- Ağ taraması (Nmap)
- Port ve servis keşfi
- Paket analizi (Wireshark)
- Temel zafiyet taramaları

## Kurulum ve Kullanım

1. Kali Linux kurulu sistem üzerinde hedef makineleri tanımlayın.
2. Terminal üzerinden aşağıdaki komutları çalıştırın:

```bash
nmap -sS -T4 -A 192.168.1.100
wireshark
