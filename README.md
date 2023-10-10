# Binary bank
This repository keeps binaries that are kindda hard to build from source<br>
All of them comes from open source
> Most of them are considered as viruses, and I strongly advise you to get them only if you know what you are doing, and if you can build them yourself will it be way much safer

## Contents

### Mimikatz
[Source](https://github.com/gentilkiwi/mimikatz)<br>
**SHA-256 checksum** :
 - ARM64
   - mimikatz.exe : 36a78837f4aa62e19bd335a4e84d3e76675c7755f6432241063e412fa50b5211
   - mimilib
     - mimilib.dll : ee3043fe9bb41ad7ee0795228e499a4c1d4bc7a4b753c3e17526cf61f528c302
     - mimilib.exp : 18c3a223ddbe57e7c2440a746b8d42d47bd034298cbf99953c3efd9480a28520
     - mimilib.lib : eed4da66fdef084bd6a9095a5d526715824ab7e1ae36ad58cf5987c189a9f354
   - mimilove
     - mimilove.exe : 17618abed524849335ed788705d0d1014f4dcd036376275dbb290aa4c9b922a4
   - mimispool
     - mimispool.dll : 80d2db19627d344a4506f5f3fd5ac6a80bf7397d5ade9a900f08f5b0b6662450
     - mimispool.exp : e13e148ff82abf631ee9e88debc7a9a444352423e26f348a5237f85ea6682886
     - mimispool.lib : 95965bd7358fe90c26cf1e47d7e4ebd8489053164b62b244026f11fd38dd1479
 - Win32 :
   - mimikatz.exe : d475e88cda6b5eb204118f5160f258df4b569d54463276de095931babbffe5b6
   - mimilib
     - mimilib.dll : 7c8e5336178d9186a455289abf694dbab7df147fb5da5790edea50d35b413aff
     - mimilib.exp : 18c3a223ddbe57e7c2440a746b8d42d47bd034298cbf99953c3efd9480a28520
     - mimilib.lib : eed4da66fdef084bd6a9095a5d526715824ab7e1ae36ad58cf5987c189a9f354
   - mimilove
     - mimilove.exe : 15d82944d90390d4f87402b612a4ec933575e2d6044bed02e362b6cb887fc569
   - mimispool
     - mimispool.dll : 325b3af5a0f2d3d3804ecaa35d31ac11ae8216f8532776d93ef476429e12ecc2
     - mimispool.exp : e13e148ff82abf631ee9e88debc7a9a444352423e26f348a5237f85ea6682886
     - mimispool.lib : 95965bd7358fe90c26cf1e47d7e4ebd8489053164b62b244026f11fd38dd1479
 - x64 :
   - mimilib
     - mimilib.dll : a59d515970ce828c56c11eac935ddc755c8a369c443bcc365969d4b9a81a7ccc
     - mimilib.exp : 915dfe0241bc255c3e30b97e9bdf1ea734f30097edf36f24e9bb08da47c2e7cf
     - mimilib.lib : 5adcf01da36f28a06cf17c3237f3667a7fa963235b9aedbd615946d4172e090f
   - mimilove
     - mimilove.exe : de5cea8178d5078584914c77f5d183952f2dfdb6d46ee11de687547d31bb374b
   - mimispool
     - mimispool.dll : 7d0f5054ed4473d5ac2cb69c40bfedbc10f00bb018fed883890bf0ab5bab32ff
     - mimispool.exp : 7fda3361c5cb941c93306e54c51abab9832df22c8d180a25a9143bdfbc9b8648
     - mimispool.lib : fabb522238481c58be4afa4f93cbdd9e417f879ade9477bf72d4ed9180fca428
**Edits** :
 - using vs 2022 instead of vs 2017 toolkit
 - \modules\rpc\kull_m_rpc_ms-rprn.h on line 7 : putted the line as comment since it created a compilation error
 - \mimilove\mimilove.c on line 25 : removed the condition and setted it as always true
> /!\ could not compile x64 mimikatz.exe

### Rubeus
[Source](https://github.com/GhostPack/Rubeus)<br>
**SHA-256 checksum** : 
 - Rubeus.exe : 7d9001eb49c3f079994b31be78461207b84a9ed806ed857c66200806bb102503
 - Rubeus.exe.config : 383b8dcb968b6bd0633658d9bb55c4acaf4c85a075aa456904a42d4e4efd5561
**Edits** :
 - MAJ 4.8

### Watson
[Source](https://github.com/rasta-mouse/Watson)<br>
**SHA-256 checksum** : 
 - Watson.exe : 19c844e9e1229b24f46ab4848ed44987f048030328fd72cf048bbd397a25a8d5
 - Watson.exe.config : 383b8dcb968b6bd0633658d9bb55c4acaf4c85a075aa456904a42d4e4efd5561
 - Watson.pdb : ccc74f15a81995e6e3f8343da539342f6e63d452fbb830d9b3bce7e5a6a76bbd
**Edits** :
 - MAJ 4.8

