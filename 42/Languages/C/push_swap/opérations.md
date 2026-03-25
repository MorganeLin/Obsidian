### Différentes opérations pour le push_swap 

**sa (*swap a*) :** Swap the first 2 elements at the top of stack a. Do nothing if there is only one element or none. 
```
void	ft_swap_a(t_list **begin)
{
	t_list	*tmp;
	if((*begin)->next == NULL || *begin == NULL)
			return ;
	tmp  = (*begin)->next;
	(*begin)->next = tmp->next;
	tmp->next = *begin;
	*begin = tmp;
}
```
Pour **sb (*swap b*)** ça doit sûrement être la même chose.

**ss (*sa & sb*)**: pour les deux opérations simultanément

**pa (*push a*)** : Take the first element at the top of b and put it at the top of a. Do nothing if b is empty.
```

```

**pb (*push b*)** :  Take the first element at the top of a and put it at the top of b. Do nothing if a is empty.
```

```

**ra (*rotate a*)** : Shift up all elements of stack a by 1. The first element becomes the last one.
```

```

**rb (*rotate b*)** : Shift up all elements of stack b by 1. The first element becomes the last one.
```

```

**rr (rotate a & rotate b*)** : pour les deux opérations simultanément.

**rra (*reverse rotate a*)** : Shift down all elements of stack a by 1.The last element becomes the first one.
```

```

**rrb (*reverse rotate b*)** : Shift down all elements of stack b by 1.The last element becomes the first one.
```

```

**rrb (*reverse rotate a & reverse rotate b*)** : pour les deux opérations simultanément.