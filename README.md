# Chinese Primary School Reading Corpus (小学语文课文语料库)

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
# Clone the corpus
git clone https://github.com/RyanL1028/chinese-reading-corpus.git

# Fetch raw text from any lesson
curl -s https://raw.githubusercontent.com/RyanL1028/chinese-reading-corpus/main/Primary%203/3B/%E7%AC%AC%E4%BA%8C%E5%8D%95%E5%85%83/7.%20%E9%B9%BF%E8%A7%92%E5%92%8C%E9%B9%BF%E8%85%BF.md
```

## Stats

- **36 lessons** across 2 semesters
- **~10,000 characters** of running text
- **Poetry + prose + fables + idioms** — all major primary school genres

## Source

Texts sourced from 义务教育教科书·语文 (PEP Edition, Ministry of Education of China). Cleaned and formatted for machine readability.

## License

The cleaned formatting and structure is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Original texts are from the public Chinese national curriculum.
