# Stacking Diffs

Simple idea: keep working on your branch and worry about reviews later.
Powerful implications.

I think most of the benefits come from **Smaller Diffs**.

**Piecewise landing**. If the bottom of the stack, i.e. closer to main, is ready, it could be merged
independently. Reduces conflicts!

**Don't stall on review**. You can continue working on the feature without waiting for full review.

**More attention to each PR**. Have you encountered something like this?
- Diff with ±10 lines changed: 100 review comments.
- Diff with ±1000 lines changed: LGTM ✅

**Better documented PRs**.

**Each PR passes checks**. That makes bisection easier.

**Lower Barrier**. Facilitates boyscout rule!

**Split Non-functional Changes**. It's easier to see if refactoring doesn't change anything if it
is split from the code implementing a feature!

⬆️ All of the above increases velocity 📈

## So?

It's possible to achieve the same with bare git, but that's very painful. There are some other tools
but they are not as good.
