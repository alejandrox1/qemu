specific_ss.add(when: 'CONFIG_SOFTMMU', if_true: [files(
  'arch_init.c',
  'balloon.c',
  'cpus.c',
  'cpu-throttle.c',
  'ioport.c',
  'memory.c',
  'memory_mapping.c',
  'qtest.c',
  'vl.c',
  'cpu-timers.c',
)])

specific_ss.add(when: ['CONFIG_SOFTMMU', 'CONFIG_TCG'], if_true: [files(
  'icount.c'
)])
