# is(selector)

`Wrapper` DOM 노드 또는 `vm`이 [selector](../selectors.md)와 일치하는지 검증합니다.

- **전달인자:**
  - `{string|Component} selector`

- **반환값:** `{boolean}`

- **예제:**

```js
import { mount } from '@vue/test-utils'
import Foo from './Foo.vue'

const wrapper = mount(Foo)
expect(wrapper.is('div')).toBe(true)
```
