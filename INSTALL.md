# 安装说明

## Claude Code

安装到当前项目：

```bash
mkdir -p .claude/skills
cp -R /path/to/dating-skill .claude/skills/create-dating
```

全局安装：

```bash
mkdir -p ~/.claude/skills
cp -R /path/to/dating-skill ~/.claude/skills/create-dating
```

## 依赖

```bash
pip3 install -r requirements.txt
```

## 验证

```bash
python3 tools/analyze_relationship_materials.py --help
python3 tools/skill_writer.py --help
python3 -m unittest discover -s tests -v
```
