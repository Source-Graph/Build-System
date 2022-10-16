# Build-System

# What Perfection Looks Like:: Bazel
- https://jmmv.dev/2020/12/google-no-clean-builds.html
- https://jmmv.dev/2019/12/bazel-strategies.html

>And yet… in spite of all the abuse… clean builds are not necessary at Google to keep the machine running building. So, how is this possible? How is Google’s build system resilient to thousands of engineers modifying build files in a gigantic monorepo, most of them without truly understanding what goes under the hood?

>The answer lies in the build tool itself: Bazel. Of course Google engineers also make mistakes in their build files. All of us do. But, when those mistakes happen, the build tool refuses to build the code upfront without giving the appearance of success. In other words: the problems that cause incremental builds to fail are real problems and the system surfaces them early on in any build2. - Julio Merino
