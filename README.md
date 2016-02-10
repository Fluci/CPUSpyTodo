# CPUSpyTodo
Todo list of CPU Spy

# Featuers
- [x] Battery mode
- [ ] Stop sampling at battery level threshold.
- [ ] Trigger alarm based on cpu usage within timeinterval

# Refactor
- [ ] Think about changing FSString to a struct type
- [ ] Think about UTF-32 and FSString
- [x] Think about FSPSSampler -> separate Tokenizer and make RowReader an Interface

# Bug Fixes
- [x] Review timing code
- [x] Investigate suddenly high timeinterval

# Clean code

- [x] Replace NSLogs with debugPrint if appropriate

# Settings
icon customization:
- [ ] displayed value (Cpu, ram, etc.)
- [ ] Categories, category colors
- [ ] font size, font type

# UX
- [x] Allow to reopen window
- [x] Clean up app menu
- [ ] Add Tool Tips to every UI element
- [x] if viewRefresh deactivated: show tip in processTable
- [x] Undo/Redo

# Future
- [ ] Observe processes and compare with white/black list -> alarm


