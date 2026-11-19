<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1">
<title>AI Prompt Library | Year 5 Mathematics</title>
<style>
:root{--ink:#26324b;--muted:#68748a;--purple:#7967d8;--line:rgba(112,126,160,.22)}
*{box-sizing:border-box}html,body{margin:0;background:transparent}body{padding:22px;font-family:Inter,"Segoe UI",Arial,sans-serif;color:var(--ink)}
.wrap{max-width:1050px;margin:auto}.hero{text-align:center;padding:28px 20px 24px;margin-bottom:20px;border:1px solid var(--line);border-radius:25px;background:rgba(255,255,255,.62);backdrop-filter:blur(12px)}
.eyebrow{display:inline-block;padding:7px 13px;border-radius:999px;color:#5c50ad;background:rgba(121,103,216,.12);font-size:12px;font-weight:800;letter-spacing:.08em;text-transform:uppercase}
h1{margin:13px 0 8px;font-size:clamp(28px,5vw,42px)}.hero p{margin:0 auto;max-width:650px;color:var(--muted);line-height:1.65}
.steps{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:18px 0 22px}.step{padding:13px 14px;border:1px solid var(--line);border-radius:16px;background:rgba(255,255,255,.55);display:flex;gap:10px;align-items:center;color:#4d5870;font-size:13px;font-weight:650}
.step b{display:grid;place-items:center;flex:0 0 27px;height:27px;border-radius:50%;color:white;background:var(--purple)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}.card{position:relative;overflow:hidden;padding:22px;border:1px solid var(--line);border-radius:22px;background:rgba(255,255,255,.78);backdrop-filter:blur(14px);box-shadow:0 12px 30px rgba(54,66,105,.07);display:flex;flex-direction:column}
.icon{width:48px;height:48px;display:grid;place-items:center;border-radius:15px;background:var(--glow);font-size:23px;margin-bottom:15px}.tag{color:var(--accent);font-size:11px;font-weight:850;letter-spacing:.09em;text-transform:uppercase}
h2{font-size:20px;margin:7px 0 8px}.desc{color:var(--muted);font-size:13px;line-height:1.55;min-height:42px;margin:0 0 15px}.prompt-label{font-size:11px;font-weight:800;color:#66718a;text-transform:uppercase;letter-spacing:.08em;margin-bottom:7px}
.prompt{flex:1;min-height:190px;padding:14px;border-radius:14px;border:1px solid rgba(110,123,154,.18);background:rgba(247,248,253,.82);color:#3f4a61;font-size:12.5px;line-height:1.6;white-space:pre-wrap}
.actions{display:grid;grid-template-columns:1fr 1fr;gap:9px;margin-top:15px}button{border:0;border-radius:12px;padding:12px 10px;cursor:pointer;font-weight:800;font-size:12px;transition:transform .15s}button:hover{transform:translateY(-2px)}button:focus-visible{outline:3px solid rgba(121,103,216,.35);outline-offset:3px}
.copy{background:var(--accent);color:white}.open{background:rgba(121,103,216,.12);color:#5c4bb8;border:1px solid rgba(121,103,216,.2)}
.tip{margin-top:18px;padding:14px 17px;border-radius:16px;border:1px dashed rgba(84,185,165,.55);background:rgba(84,185,165,.09);color:#456b68;font-size:13px;line-height:1.55}.tip strong{color:#287e70}
.toast{position:fixed;left:50%;bottom:22px;transform:translate(-50%,15px);background:#26324b;color:white;padding:11px 17px;border-radius:999px;font-size:13px;font-weight:700;opacity:0;pointer-events:none;transition:.22s;z-index:5}.toast.show{opacity:1;transform:translate(-50%,0)}
.footer{text-align:center;color:var(--muted);font-size:11px;margin:18px 0 2px}
@media(max-width:800px){.grid{grid-template-columns:1fr}.prompt{min-height:0}.steps{grid-template-columns:1fr;gap:8px}}@media(max-width:430px){body{padding:12px}.card{padding:17px}.actions{grid-template-columns:1fr}}
</style></head>
<body><div class="wrap">
<header class="hero"><div class="eyebrow">✨ Smart Learning Tool · Year 5 Maths</div><h1>AI Prompt Library</h1>
<p>Choose a prompt, copy it, and paste it into ChatGPT to get support with <strong>Combined Shapes</strong>. You are still the mathematician — AI is here to guide your thinking!</p></header>
<section class="steps"><div class="step"><b>1</b> Choose a learning mission</div><div class="step"><b>2</b> Copy the prompt and open ChatGPT</div><div class="step"><b>3</b> Paste the prompt and press Send</div></section>
<main class="grid">
<article class="card" style="--accent:#7867d8;--glow:#ded8ff"><div class="icon">📘</div><div class="tag">Mission 01 · Learn</div><h2>Learn a Concept</h2><p class="desc">Need a clear explanation before you begin? Ask AI to teach you step by step.</p><div class="prompt-label">Your ready-to-use prompt</div>
<div class="prompt" id="prompt1">I am a Year 5 student learning about combined shapes in Mathematics. Please explain what a combined shape is in simple, student-friendly language. Show me one easy example using two rectangles and explain how to find its total area step by step. Use simple words and encourage me to think along.</div>
<div class="actions"><button class="copy" onclick="copyPrompt('prompt1')">📋 Copy Prompt</button><button class="open" onclick="openChatGPT()">↗ Open ChatGPT</button></div></article>
<article class="card" style="--accent:#329b91;--glow:#c9f0e9"><div class="icon">💡</div><div class="tag">Mission 02 · Get a hint</div><h2>Get a Hint</h2><p class="desc">Stuck on a question? Receive one helpful hint at a time without being given the answer.</p><div class="prompt-label">Your ready-to-use prompt</div>
<div class="prompt" id="prompt2">I am a Year 5 student solving a question about the area of a combined shape. Please act as my maths learning coach. Give me only ONE small hint at a time to help me decide what to do next. Do not give me the final answer or solve the whole question for me. After each hint, wait for my response before giving another hint. Use simple language.</div>
<div class="actions"><button class="copy" onclick="copyPrompt('prompt2')">📋 Copy Prompt</button><button class="open" onclick="openChatGPT()">↗ Open ChatGPT</button></div></article>
<article class="card" style="--accent:#df8b43;--glow:#ffead2"><div class="icon">🧠</div><div class="tag">Mission 03 · Check</div><h2>Check My Understanding</h2><p class="desc">Review your method, discover mistakes, and improve your mathematical reasoning.</p><div class="prompt-label">Your ready-to-use prompt</div>
<div class="prompt" id="prompt3">I am a Year 5 student learning about combined shapes, area and perimeter. I will share my working or answer with you. Please check my method carefully, tell me what I did correctly, and explain any mistake in a kind and simple way. Do not immediately give me the correct final answer. Ask me one follow-up question to help me improve my understanding.</div>
<div class="actions"><button class="copy" onclick="copyPrompt('prompt3')">📋 Copy Prompt</button><button class="open" onclick="openChatGPT()">↗ Open ChatGPT</button></div></article>
</main>
<div class="tip"><strong>🌟 Remember:</strong> After ChatGPT opens, click the message box, paste your copied prompt (<strong>Ctrl + V</strong>), add your own question or working if needed, and press <strong>Send</strong>. Always check whether the AI's explanation makes mathematical sense.</div>
<div class="footer">Think · Ask · Check · Learn independently</div></div>
<div class="toast" id="toast" role="status" aria-live="polite">Prompt copied! Open ChatGPT and paste it.</div>
<script>
async function copyPrompt(id){const text=document.getElementById(id).innerText.trim();try{await navigator.clipboard.writeText(text)}catch(e){const a=document.createElement("textarea");a.value=text;a.style.position="fixed";a.style.opacity="0";document.body.appendChild(a);a.select();document.execCommand("copy");a.remove()}const t=document.getElementById("toast");t.classList.add("show");clearTimeout(window.toastTimer);window.toastTimer=setTimeout(()=>t.classList.remove("show"),2600)}
function openChatGPT(){window.open("https://chatgpt.com/","_blank","noopener,noreferrer")}
</script></body></html>
