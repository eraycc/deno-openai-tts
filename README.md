# deno-openai-tts
将微软tts文本转语音转化为兼容openai tts api格式的deno脚本
# deploy
## install
deno install -gArf jsr:@deno/deployctl
## build
deployctl deploy --project=name --prod main.ts
