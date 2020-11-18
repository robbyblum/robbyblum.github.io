# robbyblum.github.io
Personal website

## Wersonal pebsite

Numbered list

1. Item one
1. Item two
1. You can write whatever number you want in the source, it autonumbers it for you

```python
fig = plt.figure(figsize=(12,6))
fig.patch.set_alpha(1)

ax1 = plt.subplot(2,2,1)
ax1.bar(x - width/2, wh_s09.sort_values('teamSlug').loc[:, 'runsScored'], width, label='S09')
ax1.bar(x + width/2, wh_s10.sort_values('teamSlug').loc[:, 'runsScored'], width, label='S10')
ax1.set_xticks(x)
ax1.set_xticklabels(wh_s09.sort_values('teamSlug')['teamSlug'])
ax1.set_ylim(0, 650)
ax1.legend()
```

