# 68net

A SCSI to ethernet board

[My blog post](https://ronangaillard.github.io/posts/68net-a-modern-scsi2ethernet-board-part1/) for more background info 

## Contributing

To make sure Kicad and git work fluently run the following before commiting :

```bash
git config --global filter.kicad_project.clean "sed -E 's/^update=.*$/update=Date/'"
git config --global filter.kicad_project.smudge cat
git config --global filter.kicad_sch.clean "sed -E 's/#(PWR|FLG)[0-9]+/#\1?/'"
git config --global filter.kicad_sch.smudge cat
```
