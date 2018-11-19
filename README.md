# WrongConstantLintBug

Demonstrates WrongConstant bug in Lint Check after migrating to AndroidX.

```
    <issue
        id="WrongConstant"
        severity="Error"
        message="Must be one of: RecyclerView.HORIZONTAL, RecyclerView.VERTICAL"
        category="Correctness"
        priority="6"
        summary="Incorrect constant"
        explanation="Ensures that when parameter in a method only allows a specific set of constants, calls obey those rules."
        errorLine1="            return getOrientation() == VERTICAL;"
        errorLine2="                                       ~~~~~~~~">
        <location
            file="/Users/ckroetsc/WrongConstantLintBug/app/src/main/java/com/github/cckroets/wrongconstantlintbug/MainActivity.java"
            line="62"
            column="40"/>
    </issue>
```
