# Quick Start - Clerk Authentication

## 🚀 Get Started in 3 Steps

### Step 1: Get Clerk Key
1. Go to [Clerk Dashboard](https://dashboard.clerk.com)
2. Create app → API Keys → Copy Publishable Key

### Step 2: Add to Environment
```bash
cd studio
# Edit .env.local
VITE_CLERK_PUBLISHABLE_KEY=pk_test_YOUR_KEY_HERE
```

### Step 3: Run
```bash
npm run dev
```

## 📖 Full Documentation
See `CLERK_SETUP.md` for complete setup guide.

## 🔑 Where to Find Keys

### Frontend (Publishable Key)
- **Location**: Clerk Dashboard → API Keys → Publishable keys
- **Starts with**: `pk_test_` (development) or `pk_live_` (production)
- **Add to**: `studio/.env.local` as `VITE_CLERK_PUBLISHABLE_KEY`

### Backend (Secret Key) - Required Next
- **Location**: Clerk Dashboard → API Keys → Secret keys  
- **Starts with**: `sk_test_` (development) or `sk_live_` (production)
- **Add to**: `server/.env` as `CLERK_SECRET_KEY`
- **Install**: `pip install clerk-backend-sdk`

## ✅ What's Already Done
- ✅ Clerk SDK installed
- ✅ ClerkProvider configured
- ✅ Protected routes set up
- ✅ Auth headers added to API calls
- ✅ UserButton in top bar

## ⏭️ What's Next
1. Add your Clerk Publishable Key to `.env.local`
2. Test frontend authentication
3. Add backend token verification (see `AUTH_INTEGRATION_SUMMARY.md`)
