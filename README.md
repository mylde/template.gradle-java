# gradle java static analysis template
as of Oct 2020.

# google error prone
[Google Error Prone](https://github.com/google/error-prone)

# pmd
[PMD](https://pmd.github.io/)

- Mainly used to check LooseCoupling, CyclomaticComplexity and GodClass.
- Others should NOT be checked too much.
- Let google-error-prone check the error prone category.

# checkstyle
[checkstyle](https://checkstyle.sourceforge.io/)

From [google_checks.xml](https://github.com/checkstyle/checkstyle/blob/master/src/main/resources/google_checks.xml).  
The following attributes are changed.
- Indentation value, 2 to 4.

# jacoco
[JaCoCo Java Code Coverage Library](https://www.eclemma.org/jacoco/)
