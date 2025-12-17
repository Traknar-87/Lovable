# Lovable Prompt Optimizer

> **Système universel d'optimisation de prompts pour Lovable**  
> Transforme automatiquement toute demande brute en prompt structuré et professionnel.

## 🎯 Objectif

Framework réutilisable pour reformuler toute demande utilisateur en prompt optimisé Lovable, applicable à **tous types de projets** :

✅ Applications web/mobiles  
✅ Dashboards  
✅ Landing pages  
✅ Sites e-commerce  
✅ Plateformes SaaS  

## 🌍 Universalité

Ce système est **100% générique** :
- ❌ Aucune référence spécifique à un projet
- ✅ Patterns réutilisables universellement
- ✅ Adaptable à tout contexte

## 📁 Structure

```
Lovable/
├── lovable-prompt-optimizer.md           # Guide (patterns, best practices)
├── llm-instructions-lovable-optimizer.md # Instructions LLM
└── README.md                            # Documentation
```

## 🚀 Installation

### 1. Intégrer dans votre workflow
Copiez ces fichiers ou forkez ce repository

### 2. Configurer votre LLM

1. Ouvrir `llm-instructions-lovable-optimizer.md`
2. Copier le contenu complet
3. Coller dans les instructions système de votre LLM

**Les paramètres sont déjà configurés :**
```javascript
owner: "Traknar-87"
repo: "Lovable"
```

### 3. Tester
```
"Je veux une section hero pour mon application"
```

Le LLM chargera automatiquement le guide GitHub et générera un prompt optimisé.

## 💡 Principes Clés

1. **Penser en Composants** (pas de pages complètes)
2. **Contenu Réel** (pas de placeholder)
3. **Vocabulaire Atomique** (button, card, modal, etc.)
4. **Buzzwords** (Premium, Bold, Minimal, etc.)
5. **Questions de Clarification** (systématiques)

## 🎨 Patterns Disponibles

Hero Section • Feature Grid • Pricing • Forms • Navigation • Dashboard • Testimonials • Footer • CTA • Et plus...

## 🔄 Workflow

```
Demande → LLM charge guide GitHub → Analyse → Prompt optimisé + Questions
```

## ⚙️ Configuration Technique

### Prérequis
- LLM compatible GitHub MCP (Claude Desktop, etc.)
- Projet Lovable

### GitHub MCP
```javascript
github:get_file_contents({
  owner: "Traknar-87",
  repo: "Lovable",
  path: "lovable-prompt-optimizer.md"
})
```

## 🎓 FAQ

**Modifier pour chaque projet ?** Non, système universel  
**Quels LLMs ?** Tout LLM avec GitHub MCP  
**Ajouter patterns ?** Oui, éditez le fichier GitHub  
**Projets existants ?** 100% compatible  

## 📝 Version

**1.0 (Universelle)** • Décembre 2024 • Production-ready

## 📄 License

Open-source • Usage libre

---

Basé sur "Prompt better in Lovable" d'Anthropic