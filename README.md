export default function Home() { return ( <main className="min-h-screen bg-black text-white flex flex-col items-center justify-center p-8"> <div className="max-w-3xl w-full rounded-3xl border border-zinc-800 bg-zinc-950 p-10 shadow-2xl"> <h1 className="text-5xl font-bold mb-6 text-center"> AI Revenue Dashboard </h1>

<p className="text-zinc-400 text-center text-lg mb-10">
      Live MVP mit Crypto Payments, AI Infrastruktur und automatischer Skalierung.
    </p>

    <div className="grid md:grid-cols-2 gap-6 mb-10">
      <div className="rounded-2xl bg-zinc-900 p-6 border border-zinc-800">
        <h2 className="text-2xl font-semibold mb-3">System Status</h2>
        <ul className="space-y-2 text-zinc-300">
          <li>✅ Next.js Online Ready</li>
          <li>✅ Deployment vorbereitet</li>
          <li>✅ Wallet integriert</li>
          <li>✅ Skalierbar</li>
        </ul>
      </div>

      <div className="rounded-2xl bg-zinc-900 p-6 border border-zinc-800">
        <h2 className="text-2xl font-semibold mb-3">Wallet</h2>
        <div className="bg-black border border-zinc-700 rounded-xl p-4 break-all text-sm text-green-400">
          0xc5c4A7dc31e6954ee5AB045EAb07E191C869A941
        </div>
      </div>
    </div>

    <div className="rounded-2xl bg-zinc-900 p-6 border border-zinc-800 mb-8">
      <h2 className="text-2xl font-semibold mb-4">Deployment Schritte</h2>

      <ol className="space-y-3 text-zinc-300 list-decimal list-inside">
        <li>Projekt nach GitHub pushen</li>
        <li>Mit Vercel verbinden</li>
        <li>Deploy klicken</li>
        <li>Automatische Live-URL erhalten</li>
      </ol>
    </div>

    <div className="flex flex-col md:flex-row gap-4">
      <a
        href="https://vercel.com"
        target="_blank"
        className="flex-1 bg-white text-black font-semibold py-4 rounded-2xl text-center hover:opacity-90 transition"
      >
        Deploy mit Vercel
      </a>

      <a
        href="https://github.com"
        target="_blank"
        className="flex-1 bg-zinc-800 border border-zinc-700 py-4 rounded-2xl text-center hover:bg-zinc-700 transition"
      >
        GitHub öffnen
      </a>
    </div>
  </div>
</main>

) }# -
