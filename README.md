# claude-skills-mn

**Монгол хэрэглэгчдэд зориулсан [Claude](https://claude.ai) skill-үүдийн цуглуулга.**

Монгол хэл, монгол бичиг, статистик, төрийн цахим үйлчилгээ, AI агент бүтээх, өдөр тутмын бүтээмжид Claude-ыг илүү ухаалаг ажиллуулах зааврууд.

*A collection of Claude Agent Skills for Mongolian speakers — Mongolian language & traditional script, statistics, public service design, and productivity.*

## Суулгах

Claude Code дээр:

```
/plugin marketplace add baynorgikh/claude-skills-mn
/plugin install mongol-bichig-teacher@claude-skills-mn
```

Бусад skill-ийг мөн адил `/plugin install <нэр>@claude-skills-mn` гэж суулгана.

Claude.ai (вэб/десктоп) дээр: `plugins/<нэр>/skills/<нэр>/` хавтсыг zip болгоод **Settings → Capabilities → Skills → Upload skill**-ээр оруулна.

## Skill-үүд

### 📚 Боловсрол, хэл

| Skill | Юу хийдэг |
|---|---|
| [mongol-bichig-teacher](plugins/mongol-bichig-teacher/skills/mongol-bichig-teacher/SKILL.md) | Монгол (уйгуржин) бичиг заах, кирилл ↔ монгол бичиг хөрвүүлэх, галиглах, нөхцөл залгах дүрэм, хос бичгийн албан баримт |
| [mongolian-language-teacher](plugins/mongolian-language-teacher/skills/mongolian-language-teacher/SKILL.md) | Зөв бичлэг, үгийн утга, зөв бичих дүрэм (§1–§64), найруулгын алдааг журамласан болон тайлбар толиор баталгаажуулж засах |
| [heiman-statistics-mn](plugins/heiman-statistics-mn/skills/heiman-statistics-mn/SKILL.md) | Сэтгэл судлалын статистикийг монголоор заах: t-тест, ANOVA, χ², нөлөөний хэмжээ, SPSS, APA тайлагнал |

### 🏛️ Төрийн үйлчилгээ

| Skill | Юу хийдэг |
|---|---|
| [oecd-public-service-design](plugins/oecd-public-service-design/skills/oecd-public-service-design/SKILL.md) | Төрийн цахим үйлчилгээг OECD-ийн 3 тулгуур, 9 зарчмаар үнэлэх, төлөвлөх, бодлогын баримтад олон улсын жишиг оруулах |

### ⚙️ Бүтээмж, AI агент

| Skill | Юу хийдэг |
|---|---|
| [ai-agent-builder](plugins/ai-agent-builder/skills/ai-agent-builder/SKILL.md) | Код мэдэхгүй хүн ч анхны AI агентаа барих: brain dump → CLAUDE.md → subagent → human-in-the-loop |
| [task-brief-builder](plugins/task-brief-builder/skills/task-brief-builder/SKILL.md) | Том ажил өгөхөөс өмнө санаагаа нэг нэгээр асууж тодруулж, 4 хэсэгтэй brief болгох |
| [daily-work-report](plugins/daily-work-report/skills/daily-work-report/SKILL.md) | Өдрийн ажлын файл, Google Calendar, тэмдэглэлээс нотолгоонд суурилсан албан ёсны .docx тайлан гаргах |

## Бүтэц

```
claude-skills-mn/
├── .claude-plugin/marketplace.json   # Plugin marketplace-ийн жагсаалт
└── plugins/<нэр>/
    ├── .claude-plugin/plugin.json
    └── skills/<нэр>/SKILL.md          # Skill-ийн заавар
```

## Хувь нэмэр оруулах

Алдаа олсон, сайжруулах санаа байвал [Issue](https://github.com/baynorgikh/claude-skills-mn/issues) нээх эсвэл Pull Request илгээнэ үү. Шинэ skill санал болгож болно.

## Лиценз

[MIT](LICENSE)
