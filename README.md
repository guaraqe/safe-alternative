# total-alternative

This library exports total versions for Prelude partial functions
using an `Alternative` interface where `empty` represents the result
for invalid inputs.

The `Alternative` interface allows them to be specialized to:
- `Maybe`
- `List`
- `Vector`
- `EitherT`
- `ExceptT`
- `Validation` : [Hackage](https://hackage.haskell.org/package/validation)
- `Success` : [Hackage](https://hackage.haskell.org/package/success)
