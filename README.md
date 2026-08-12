# （根据2022年版课程标准修订）义务教育教科书

Open corpus of Chinese primary school reading texts from the PEP (人教版) Chinese language textbooks (义务教育教科书·语文). Clean, plain-text markdown — ready for NLP, language learning apps, and educational tools.

## Contents

| Grade | Semester | Lessons | Units |
|-------|----------|---------|-------|
| 3A (三年级上册) | Semester 1 | 26 | 8 |
| 3B (三年级下册) | Semester 2 | 6 | 2 |

## Structure

```
Primary 3/
├── 3A/                          # 三年级上册
│   ├── 第一单元/                  # Unit 1
│   │   ├── 1. 大青树下的小学.md
│   │   ├── 2. 花的学校.md
│   │   └── 3. 不懂就要问.md
│   ├── 第二单元/                  # Unit 2
│   │   ├── 4. 古诗三首/           # Poetry
│   │   │   ├── 4A. 望洞庭.md
│   │   │   ├── 4B. 山行.md
│   │   │   └── 4C. 夜书所见.md
│   │   ├── 5. 铺满金色巴掌的水泥道.md
│   │   ├── 6. 秋天的雨.md
│   │   └── 7. 听听，秋的声音.md
│   └── ...
└── 3B/                          # 三年级下册
    ├── 第一单元/
    │   └── 1. 古诗三首/
    │       ├── 1A. 绝句.md
    │       ├── 1B. 惠崇春江晚景.md
    │       └── 1C. 三衢道中.md
    └── 第二单元/
        ├── 6. 陶罐和铁罐.md
        ├── 7. 鹿角和鹿腿.md
        └── 8. 池子与河流.md
```

## File Format

Each `.md` file contains:
- **Line 1**: Lesson number and title
- **Remaining lines**: Clean Chinese text, one paragraph per line, no markup

## Usage

```bash
# Clone the full corpus
git clone https://github.com/RyanL1028/chinese-official-syllabus.git

# Or fetch a single lesson via raw URL
# Path pattern: Primary 3/{semester}/{unit}/{lesson}.md
# (URL-encode any Chinese characters in the path)
```

## Stats

- **36 lessons** across 2 semesters
- **~10,000 characters** of running text
- **Poetry + prose + fables + idioms** — all major primary school genres

---

## Disclaimer

The texts in this repository are sourced from the official Chinese national curriculum (义务教育教科书·语文, PEP Edition, Ministry of Education of the People's Republic of China). All content, including the original texts, lesson titles, and curricular structure, belongs to the original copyright holders.

- **My role**: I have only cleaned and formatted these publicly available educational texts into plain-text markdown for easier access. I do not claim any ownership over the original content.
- **Purpose**: This repository exists solely for educational and research purposes — to support Chinese language learners, NLP researchers, and educational tool developers.
- **No commercial use**: These files are not intended for commercial distribution or sale.
- **No infringement intended**: This is a good-faith effort to make China's national curriculum more accessible to learners worldwide. If you are a rights holder and have concerns, please contact me and I will promptly remove the content.

By using this repository, you acknowledge that the original texts remain the intellectual property of their respective owners.
