# UPSTREAM · flarum-passkey-login fork

## Upstream

| 项 | 值 |
|---|---|
| Upstream repository | `https://github.com/shaokeyibb/flarum-passkey-login` |
| Fixed base commit | `132ccc069270c25f05ec10f53853c72eca2bc753` (`132ccc0 chore: update deps`) |
| Fork repository | `https://github.com/0xffff-one/flarum-passkey-login` |
| Sync direction | upstream → fork（镜像 + 维护，不向 upstream 回推） |
| License | Apache-2.0，见 `LICENSE.md` |

## 同步原则

- 以固定 base commit `132ccc0` 为同步基准；上游新提交先审阅后再合入。
- 保留上游 Apache-2.0 LICENSE 与 attribution（作者 `HikariLan`、composer `authors`、`support` 指向）原样不动。
- 扩展行为（WebAuthn API、认证流程、schema、route、settings key、JS public API）不在 fork 内修改。
- 本 fork 的维护范围：镜像上游、固定修订、被应用侧作为 path package snapshot 的 provenance 来源。

## 验证

```sh
git rev-parse HEAD  # 应为 132ccc069270c25f05ec10f53853c72eca2bc753
git status          # 除 UPSTREAM.md 外无改动
```
