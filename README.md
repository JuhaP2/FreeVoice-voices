# FreeVoice voices (DirectML / ONNX)

Downloads for the FreeVoice app. FreeVoice fetches one voice when you click it; these files are not meant to be used on their own.

Each voice is the original community RVC v2 model converted to ONNX (fp16) with a reduced retrieval index, so it runs with ONNX Runtime DirectML without PyTorch. Conversion does not change the licence: **each voice stays under the licence and use restrictions of its original source**, linked below. Only voices published under OpenRAIL are included.

| Voice | File | Author | Original source | Licence |
|---|---|---|---|---|
| Morgan Freeman · AI | `morgan-freeman` | CxronaBxndit | [CxronaBxndit/Morgan-Freeman](https://huggingface.co/CxronaBxndit/Morgan-Freeman) | openrail |
| Stewie Griffin · AI | `stewie-griffin` | AJ Capizzi | [maoeee/RVC-Models](https://huggingface.co/maoeee/RVC-Models) | openrail |
| Lois Griffin · AI | `lois-griffin` | skippy_lean | [maoeee/RVC-Models](https://huggingface.co/maoeee/RVC-Models) | openrail |
| Severus Snape / Alan Rickman · AI | `severus-snape` | RenZ97 | [RenZ97/SeverusSnape](https://huggingface.co/RenZ97/SeverusSnape) | openrail |
| Patrick Star · AI | `patrick-star` | quichequill | [quichequill/RVC-V2_Models](https://huggingface.co/quichequill/RVC-V2_Models) | openrail |
| Mr. Krabs · AI | `mr-krabs` | quichequill | [quichequill/RVC-V2_Models](https://huggingface.co/quichequill/RVC-V2_Models) | openrail |
| Plankton · AI | `plankton` | quichequill | [quichequill/RVC-V2_Models](https://huggingface.co/quichequill/RVC-V2_Models) | openrail |
| Eric Cartman · AI | `eric-cartman` | UkrShitMashup / YXXXNZ | [YXXXNZ/EricCartmanV1.1_RVC](https://huggingface.co/YXXXNZ/EricCartmanV1.1_RVC) | openrail |
| Stan Marsh · AI | `stan-marsh` | Stan Malkinson | [stanmalkinson199/StanMarsh](https://huggingface.co/stanmalkinson199/StanMarsh) | openrail |
| Shrek · Mike Myers · AI | `shrek` | SyberGen | [SyberGen/Shrek-VModels](https://huggingface.co/SyberGen/Shrek-VModels) | openrail |
| Paavo Pesusieni / SpongeBob · AI | `spongebob` | quichequill | [quichequill/RVC-V2_Models](https://huggingface.co/quichequill/RVC-V2_Models) | openrail |
| Minionit · J. A. Taylor · AI | `minions-jat` | WoomyPearl | [WoomyPearl/RVC-Model-Palace](https://huggingface.co/WoomyPearl/RVC-Model-Palace) | openrail |
| Bane · Tom Hardy · AI | `bane-tom-hardy` | YourLocalWorm | [YourLocalWorm/BatmanModels](https://huggingface.co/YourLocalWorm/BatmanModels) | openrail |
| Joker · Heath Ledger · AI | `joker-heath-ledger` | Homiebear | [Homiebear/HeathJoker](https://huggingface.co/Homiebear/HeathJoker) | openrail |

Shared models: `content.onnx` is the HuBERT-base content encoder (fairseq, MIT) and `rmvpe.onnx` the RMVPE pitch model, both as distributed with the RVC project (MIT); `mel_basis.npy` is a librosa mel filter bank.

Voices imitating real people must not be used to deceive, impersonate or harass anyone. Follow the use restrictions of each model's OpenRAIL licence.
