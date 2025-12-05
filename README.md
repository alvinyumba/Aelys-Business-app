export default function Home() {
  return (
    <main className="flex min-h-screen flex-col items-center justify-center bg-gray-100 p-6">
      <div className="max-w-xl text-center bg-white shadow-xl p-8 rounded-2xl">
        <h1 className="text-3xl font-bold mb-4 text-gray-900">
          Bienvenue sur Aelys Business
        </h1>

        <p className="text-gray-600 mb-6">
          Votre application est bien déployée !  
          Vous pouvez maintenant ajouter vos composants, vos formulaires, vos API et toute votre logique métier.
        </p>

        <a
          href="/contact"
          className="bg-blue-600 text-white px-6 py-3 rounded-xl shadow hover:bg-blue-700 transition"
        >
          Aller à la page Contact
        </a>
      </div>
    </main>
  );
}
