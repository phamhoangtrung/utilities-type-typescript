# ultility-type-typescript

```tsx

interface Storage {
  getObjectItem:<T extends string>(key:T)=>LocalStorageValue<T>;
}

type LocalStorageKey = keyof LocalStorage
type LocalStorageValue<T> = T extends LocalStorageKey ? LocalStorage[...
```

[Playground Link](https://www.typescriptlang.org/play?#code/FASwdgLgpgTgZgQwMZQAQGUIHsYIOZoDewqqBEA8gEYBWUSEAktALYBcAPACqpQAe0MABMAzqhEQY4PAD4AFAGsoATzZcAlAF4ZAGSxIEAG0w58UAGpGArlG4yA3MAC+wYBGUAHNHoPHsuAgBpFVRNVCVlLDhUHyMTAKg3T299OP8zS0MbO1DUHn5BURjUv1MgkIB+Yt94swBtLgBdNlQEMGVHUEhYRBRqtLKiElQrEVgW4lJSMAQWKDYJKTA8ABph0jM2MCsWKlhhp0dSbCUwNgADACEoBFhUABJCReknc6PUJCwsBRB57d3YI4XF1oPBkCkaukCKhJq0hEIYFARCI2LDSB4ABZYMBQAByOz2MC2BP2pBcwMMJVqBAAdORqHQGMwoCxcnArGAGCBsYoVOpYZ8wBJUDQRNjmaywhAMSARHSoExWLzlOphoiIFYYGARWKwBLUAAyA2oABS6AouJpHgQMDGclF4tYquBwEFwpOUG1YUpkMG8sotHoipZcgA5B6wKHVW6IHCEUixN6qVCoP6GUGJWGEPDEcio8AgA)
