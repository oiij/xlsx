# UseXLSX

Features:

- Bundle with [tsup](https://github.com/egoist/tsup)
- Test with [vitest](https://vitest.dev)

# Usage

### 安装

```bash
pnpm add @oiij/xlsx
```

### 使用

```vue
<script setup lang="ts">
import { useXLSX } from '@oiij/xlsx'
const { transform, json2XLS, json2XLSX, json2CSV, exportSheet, json2Sheet, } = useXLSX()
</script>
```

## License

MIT
