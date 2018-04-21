scala_library(
  name = 'hello-library',
  sources = globs('*.scala')
)

jvm_binary(name = 'hello',
  main = 'Hello',
  dependencies = [':hello-library']
)
