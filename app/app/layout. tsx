import { Analytics } from '@vercel/analytics/next'
import type { Metadata, Viewport } from 'next'
import './globals.css'

export const metadata: Metadata = {
  title: 'Bac Rima19 | طريقك إلى النجاح',
  description: 'منصة Bac Rima19 التعليمية لمرافقتك في رحلة النجاح في البكالوريا.',
  generator: 'Bac Rima19',
  icons: { icon: '/icon.svg', apple: '/apple-icon.png' },
}

export const viewport: Viewport = {
  colorScheme: 'dark',
  themeColor: '#0a0c18',
  userScalable: false,
}

export default function RootLayout({ children }: Readonly<{ children: React.ReactNode }>) {
  return <html lang="ar" dir="rtl"><body className="antialiased">{children}{process.env.NODE_ENV === 'production' && <Analytics />}</body></html>
}
