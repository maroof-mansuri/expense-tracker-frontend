# Expense Tracker Frontend - Deployment Guide

## 🚀 Deployment Status: READY

Your frontend is configured to work with the Vercel backend deployment.

## 📋 Configuration

- **API URL**: Points to Vercel backend (`https://expense-tracker-backend.vercel.app`)
- **Build Tool**: Vite
- **Theme**: Light blue theme

## 🔧 Environment Variables

No environment variables needed for frontend - it uses the backend API.

## 📱 Live URL

**Frontend**: https://expense-tracker-frontend.vercel.app

## 🧪 Test the App

1. Visit the frontend URL
2. Try signup/login
3. Add/view expenses
4. Check the dashboard

## 🔗 API Endpoints

- **Signup**: `POST /api/v1/users/register`
- **Login**: `POST /api/v1/users/login`
- **Transactions**: `GET/POST /api/v1/transactions`

## 📞 Support

If signup doesn't work, check that the backend is deployed and environment variables are set.