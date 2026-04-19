# Update Plan for works.html - Limit Portfolio to 5 Categories

## Completed: 2/5 ✅

- [x] 1. Create TODO-works.md to track progress
- [x] 2. Understand works.html structure (Supabase fetch with filter query, dynamic grid, web showcase)
- [ ] 3. Plan detailed:
  - Define const ALLOWED_CATEGORIES = ['Brand Design', 'Promotion Design', 'Social Media Management', 'Tech Development', 'Audio Visual']
  - Modify fetchAllWorks(): fetch all, then .filter(p => ALLOWED_CATEGORIES.includes(p.category))
  - Update filter buttons to only show these 5 + All
  - Keep 'All' show all 5 categories projects
- [ ] 4. Edit JS in works.html
- [ ] 5. Test & complete

**Dependent files:** None

**Followup:** Refresh works.html, test filters

## Completed: 3/5 ✅

- [x] 1. Create TODO-works.md to track progress
- [x] 2. Understand works.html structure (Supabase fetch with filter query, dynamic grid, web showcase)
- [x] 3. Plan detailed confirmed
  - ALLOWED_CATEGORIES array defined
  - fetchAllWorks modified to client-filter projects
  - Filter buttons updated to 5 categories + All

**Exact edit blocks identified in works.html JS:**
1. Add ALLOWED_CATEGORIES after Supabase config
2. Replace query logic in fetchAllWorks
3. Replace filterContainer innerHTML

## Completed: 4/5 ✅

- [x] 1. Create TODO-works.md
- [x] 2. Understand works.html structure
- [x] 3. Plan detailed confirmed
- [x] 4. Edit works.html:
  - Added ALLOWED_CATEGORIES array ✅
  - Client-side filter in fetchAllWorks ✅ (fetch all then filter)
  - Filter buttons reduced to 5 + All ✅

**Linter errors fixed:** Removed duplicate 'projects' declarations

**Test:** works.html now shows only projects from the 5 categories. 'All' shows all matching, individual filters show specific category.

**Next:** Final test & completion
