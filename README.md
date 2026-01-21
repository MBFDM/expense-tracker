# Expense Tracker - Application de Gestion des Dépenses Personnelles

Une application web complète de gestion des dépenses personnelles construite avec Next.js (frontend) et Laravel (backend).

## Fonctionnalités

### Frontend (Next.js)
- ✅ Authentification (Login/Register)
- ✅ Liste des dépenses avec pagination
- ✅ Formulaire d'ajout/modification de dépenses
- ✅ Validation côté client
- ✅ Filtrage par catégorie
- ✅ Recherche par description
- ✅ Affichage du total des dépenses
- ✅ Mode sombre/clair
- ✅ Design responsive (mobile-first)
- ✅ Suppression avec confirmation

### Backend (Laravel)
- ✅ Authentification avec Laravel Sanctum
- ✅ API REST complète
- ✅ Validation des données
- ✅ Gestion des erreurs avec codes HTTP appropriés
- ✅ Base de données PostgreSQL
- ✅ Pagination
- ✅ Relations utilisateur-dépenses

## Technologies Utilisées

### Frontend
- **Next.js 18** - Framework React avec App Router
- **TypeScript** - Typage statique
- **Tailwind CSS** - Styling utilitaire
- **React Hook Form** - Gestion des formulaires
- **Context API** - Gestion d'état (thème et authentification)

### Backend
- **Laravel 10** - Framework PHP
- **PostgreSQL** - Base de données
- **Laravel Sanctum** - Authentification API
- **Eloquent ORM** - ORM pour la base de données

### Infrastructure
- **Docker** - Conteneurisation
- **Docker Compose** - Orchestration des services

## Installation et Démarrage

### Prérequis
- Docker et Docker Compose
- Node.js 18+ (pour le développement local)
- PHP 8.2+ (pour le développement local)
- Composer (pour le développement local)

### Avec Docker (Recommandé)

1. **Cloner le repository**
```bash
git clone <repository-url>
cd expense-tracker