# Git Hooks (공유)

이 폴더의 훅은 **팀 공유용**입니다. clone 후 한 번만 활성화하세요:

```bash
git config core.hooksPath .githooks
```

## pre-commit

`docs/*.mdx` 를 변경했는데 `docs/updates.mdx`(최근 업데이트 로그)는 그대로면
커밋 시 안내를 출력합니다. **커밋을 막지 않습니다**(리마인더 전용).

의미 있는 문서 추가/개선이면 `docs/updates.mdx` 맨 위에 `<Update>` 블록을 추가해주세요.
