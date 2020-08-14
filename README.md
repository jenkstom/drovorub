# drovorub

This is intended to store code and instructions from the FBI/NSA for detecting DROVORUB. If I can ever find it.

PDF is here: https://media.defense.gov/2020/Aug/13/2002476465/-1/-1/0/CSA_DROVORUB_RUSSIAN_GRU_MALWARE_AUG_2020.PDF

Volatility tools: 

$ git clone https://github.com/volatilityfoundation/volatility

$ cd volatility

$ sudo python setup.py install

$ sudo python /usr/local/bin/vol.py -f /root/working/mem.img --profile=LinuxCentOS65x64 linux_hidden_modules

I'm not having much luck so far

