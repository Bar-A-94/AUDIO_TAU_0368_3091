<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Audio%20Processing%20with%20DL&fontSize=40&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Signals%2C%20spectrograms%2C%20DTW%20and%20CTC&descSize=15&descAlignY=58" width="100%" />

**Advanced Topics in Audio Processing using Deep Learning · Tel Aviv University**<br/><sub>Instructor: Tal Rosenwein</sub>

<img src="https://img.shields.io/badge/%F0%9F%8E%93%20Tel%20Aviv%20University-30363d?style=for-the-badge" />
<img src="https://img.shields.io/badge/Course-0368--3091-30363d?style=for-the-badge" />
<img src="https://img.shields.io/badge/Python-30363d?style=for-the-badge&logo=python&logoColor=FFD43B" />
<img src="https://img.shields.io/badge/Jupyter-30363d?style=for-the-badge&logo=jupyter&logoColor=F37626" />

</div>

<br/>

> [!NOTE]
> My solutions to the audio processing course assignments (A1 done together with Rom Drori).

## 📚 Assignments

| | Assignment | Topics |
|:-:|---|---|
| 🔊 | **[A1: Digital signal processing](A1/)** | Written DSP questions and a technical notebook · a stereo hearing resource (Audacity project) |
| 🗣️ | **[A2: Speech matching and alignment](A2/)** | **Mel spectrograms** · **DTW** distance matrices and threshold search · automatic gain control (AGC) · **CTC** forward algorithm and forced alignment |

Written solution: [A1](A1/AUDIO_A1_written.pdf) · A2 code: [`main.py`](A2/code/main.py)

## 🗂️ Structure

```
AUDIO_TAU_0368_3091/
├── A1/
│   ├── code/code.ipynb            # technical part
│   ├── AUDIO_A1_written.pdf       # written part
│   ├── resources/                 # audio resources
│   └── supplied_files/            # assignment
├── A2/
│   ├── code/main.py               # mel specs, DTW, CTC forward + alignment
│   ├── code/utils/agc.py          # automatic gain control
│   ├── code/utils/segment.py      # segmentation
│   └── supplied_files/            # assignment + force_align.pkl
└── requirements.txt
```

## 🚀 Run

```bash
pip install -r requirements.txt
python A2/code/main.py
```

## 🙏 Acknowledgments

Thanks to **Tal Rosenwein** for the course. Background reading: *Linear Systems and Signals* by B. P. Lathi.

> [!IMPORTANT]
> These are my personal solutions, shared for learning purposes. If you are currently taking this course, please follow its academic integrity guidelines.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" />
