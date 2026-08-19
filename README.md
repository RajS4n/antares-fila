# Fila do Financeiro — Antares

Tela de revisão das mensagens do agente financeiro. É só a casca: os dados vêm
da Edge Function `fila` no Supabase, e o acesso é por senha.

Publicada em GitHub Pages porque o Supabase sandboxa HTML servido por ele
(`Content-Security-Policy: default-src 'none'; sandbox` bloqueia todo o
JavaScript) e o conector da Vercel só enxerga um projeto.
