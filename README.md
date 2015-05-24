
# progress --> postal.js #402

- azk PR: https://github.com/azukiapp/azk/pull/402


#### Postal.js (utils/postal_helper.js)

- https://www.npmjs.com/package/postal


#### Formato

- channel: '**azk**'
- topic: '**system.run._wait_available.status**'

  - arquivo: src/system/run.js
    - docker/run
    - system/run
  - função: _wait_available()
  - tipo: **status**


#### Habilitar inspeção de todos os "publishers"

```
export AZK_SUBSCRIBE_POSTAL=#
```