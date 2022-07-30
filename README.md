
#pages
	_app.page.tsx
	index.page.tsx

#src
	sidebar
		sidebar.component.tsx
		sidebar.stories.tsx
		sidebar.data.ts

	profile
		profile.component.tsx
		profile.stories.tsx
		profile-username.component.tsx
		profile-username.stories.tsx
		profile-avatar.component.tsx
		profile-avatar.stories.tsx
		
	icons
		icons-gallery.stories.tsx --should bring info of props
		icon-add.component.tsx
		icon-remove.component.tsx	

	middlewares
		auth.middleware.component.tsx
		after-auth.middleware.component.tsx
		
	fetching-apis
		_fetcher.api.ts
		tasks.api.ts
		projects.api.ts

	sockets
		

#Naming code
	class/function parent: 
		rules: first word should be uppercase
		examples:
			Appbar
			AuthController
	