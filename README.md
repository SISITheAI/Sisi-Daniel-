import React from "react";
import ChatBot from "./components/ChatBot";
import ImageGenerator from "./components/ImageGenerator";

export default function App() {
  return (
    <div className="min-h-screen bg-gray-900 text-white p-4">
      <header className="text-center mb-6">
        <h1 className="text-4xl font-bold">Sisi Daniel - L'intelligence de la rue</h1>
        <p className="text-sm text-gray-400">Philosophe, drôle, banlieue & futé</p>
      </header>
      <main className="max-w-3xl mx-auto space-y-8">
        <ChatBot />
        <ImageGenerator />
      </main>
    </div>
