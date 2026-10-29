# ernie-routine-env

Empty project cloned by the Insurance DataOps cloud routines (dayag.agent account) only for its `.claude/settings.json`:
it lowers `MAX_MCP_OUTPUT_TOKENS` so that every MCP tool answer above ~1500 tokens is saved to a file on disk
instead of shown inline. The routine then copies files with Python and never retypes data by hand. No code, no data.
