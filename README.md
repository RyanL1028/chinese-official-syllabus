# （根据2022年版课程标准修订）义务教育教科书

Open corpus of Chinese primary school reading texts from the PEP (人教版) Chinese language textbooks (义务教育教科书·语文). Clean, plain-text markdown — ready for NLP, language learning apps, and educational tools.

## Contents

| Grade | Semester | Lessons | Units |
|-------|----------|---------|-------|
| 3A (三年级上册) | Semester 1 | 30 | 8 |
| 3B (三年级下册) | Semester 2 | 36 | 8 |

## Structure

```
Primary 3/
├── 3A/ 三年级上册 (Semester 1)
│   ├── 第一单元/                1. 大青树下的小学 · 2. 花的学校 · 3. 不懂就要问
│   ├── 第二单元/                4A-C. 古诗三首 (望洞庭 · 山行 · 夜书所见) · 5. 铺满金色巴掌的水泥道 · 6. 秋天的雨 · 7. 听听，秋的声音
│   ├── 第三单元/                8. 总也倒不了的老屋 · 9. 犟龟 · 10. 小狗学叫
│   ├── 第四单元/                11. 宝葫芦的秘密（节选）· 12. 在牛肚子里旅行 · 13. 一块奶酪
│   ├── 第五单元/                14. 搭船的鸟 · 15. 金色的草地
│   ├── 第六单元/                16. 富饶的西沙群岛 · 17. 海滨小城 · 18. 美丽的小兴安岭 · 19. 香港，璀璨的明珠
│   ├── 第七单元/                20A-C. 古诗三首 (鹿柴 · 望天门山 · 饮湖上初晴后雨) · 21. 大自然的声音 · 22. 读不完的大书
│   └── 第八单元/                23. 司马光 · 24. 一定要争气 · 25. 手术台就是阵地 · 26. 一个粗瓷大碗
└── 3B/ 三年级下册 (Semester 2)
    ├── 第一单元/                1A-C. 古诗三首 (绝句 · 惠崇春江晚景 · 三衢道中) · 2. 燕子 · 3. 荷花 · 4A-D. 昆虫备忘录 (复眼 · 花大姐 · 独角仙 · 蚂蚱)
    ├── 第二单元/                5. 守株待兔 · 6. 会摇尾巴的狼 · 7. 鹿角和鹿腿 · 8. 池子与河流
    ├── 第三单元/                9. 海底世界 · 10. 石鲎 · 11. 小虾
    ├── 第四单元/                12A-C. 古诗三首 (元日 · 清明 · 九月九日忆山东兄弟) · 13. 纸的发明 · 14. 赵州桥 · 15. 一幅名扬中外的画
    ├── 第五单元/                16. 胡萝卜先生的长胡子 · 17. 我变成了一棵树
    ├── 第六单元/                18A-C. 童年的水墨画 (溪边 · 江上 · 林中) · 19. 肥皂泡 · 20. 灰雀 · 21. 我不能失信
    ├── 第七单元/                22. 火烧云 · 23. 暴风雨来临之前 · 24. 我们奇妙的世界
    └── 第八单元/                25. 慢性子裁缝和急性子顾客 · 26. 漏 · 27. 枣核
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

- **66 lessons** across 2 semesters, 16 units
- **~25,000 characters** of running text
- **Poetry + prose + fables + idioms** — all major primary school genres

---

## Disclaimer

The texts in this repository are sourced from the official Chinese national curriculum (义务教育教科书·语文, PEP Edition, Ministry of Education of the People's Republic of China). All content, including the original texts, lesson titles, and curricular structure, belongs to the original copyright holders.

- **My role**: I have only cleaned and formatted these publicly available educational texts into plain-text markdown for easier access. I do not claim any ownership over the original content.
- **Purpose**: This repository exists solely for educational and research purposes — to support Chinese language learners, NLP researchers, and educational tool developers.
- **No commercial use**: These files are not intended for commercial distribution or sale.
- **No infringement intended**: This is a good-faith effort to make China's national curriculum more accessible to learners worldwide. If you are a rights holder and have concerns, please contact me and I will promptly remove the content.

By using this repository, you acknowledge that the original texts remain the intellectual property of their respective owners.
