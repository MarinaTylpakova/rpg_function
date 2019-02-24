import emoji


def step_1():
    print(emoji.emojize('Маленький котик любит печеньки ️:cat_face:  \n'
                        'Дадим котику печеньки? :cookie:'
                        ))
    step = input()
    var = {'да': True, 'нет': False}
    while step not in var:
        print('Выберите: {}/{}'.format(*var))
        step = input()

    if var[step]:
        return step_2_yes()
    return step_2_no()


def step_2_yes():
    print(emoji.emojize('К печенькам нужно молочко :glass_of_milk:  \n'
                        'Дадим котику молоко?'
                        ))
    step = input()

    if step == 'да':
        return step_31_yes()
    elif step == 'нет':
        return step_31_no()
    else:
        print('Выберите: да/нет')
        step_2_yes()


def step_2_no():
    print('Котик расстроился \nПопробуем это исправить?')
    step = input()

    if step == 'да':
        return step_32_yes()
    elif step == 'нет':
        return step_32_no()
    else:
        print('Выберите: да/нет')
        step_2_no()


def step_31_yes():
    print('Класс! Осталось совсем чуть-чуть  \n'
          'Позовем друзей?')
    step = input()
    var = ['да', 'нет']

    if step == var[0]:
        return step_41_yes()
    elif step == var[1]:
        return step_41_no()
    else:
        print('Выберите: {}/{}'.format(*var))
        step_31_yes()


def step_31_no():
    print(emoji.emojize('Может тогда чаю? :hot_beverage:️'))
    step = input()
    var = ['да', 'нет']

    if step == var[0]:
        return step_42_yes()
    elif step == var[1]:
        return step_42_no()
    else:
        print('Выберите: {}/{}'.format(*var))
        step_31_no()


def step_32_yes():
    print(emoji.emojize('Нальем котику вина? ️:wine_glass:'))
    step = input()
    var = ['да', 'нет']

    if step == var[0]:
        return step_43_yes()
    elif step == var[1]:
        return step_43_no()
    else:
        print('Выберите: {}/{}'.format(*var))
        step_32_yes()


def step_32_no():
    print(emoji.emojize('Вы обидели котика :crying_cat_face:\n'
                        'GAME OVER'
                        ))


def step_41_yes():
    print(emoji.emojize('Позовем маленькую уточку?  :duck:'))
    step = input()
    var = ['да', 'нет']

    if step == var[0]:
        return step_51_yes()
    elif step == var[1]:
        return step_51_no()
    else:
        print('Выберите: {}/{}'.format(*var))
        step_41_yes()


def step_41_no():
    print(emoji.emojize('Тогда котику достанется больше ️:winking_face:️'))


def step_42_yes():
    print(emoji.emojize('Котик доволен :thumbs_up:'))


def step_42_no():
    print(emoji.emojize(':pensive_face:'))


def step_43_yes():
    print(emoji.emojize('Тогда еще пиццу?  :pizza:'))
    step = input()
    var = ['да', 'нет']

    if step == var[0]:
        return step_52_yes()
    elif step == var[1]:
        return step_52_no()
    else:
        print('Выберите: {}/{}'.format(*var))
        step_43_yes()


def step_43_no():
    print(emoji.emojize('Может тогда подарим котику шарик? :balloon:'))
    step = input()
    var = ['да', 'нет']

    if step == var[0]:
        return step_53_yes()
    elif step == var[1]:
        return step_53_no()
    else:
        print('Выберите: {}/{}'.format(*var))
        step_43_no()


def step_51_yes():
    print(emoji.emojize('Здорово! Все получилось :thumbs_up:'))


def step_51_no():
    print(emoji.emojize('Тогда котику достанется больше ️:winking_face:️'))


def step_52_yes():
    print(emoji.emojize('Супер! Котик доволен и совсем не обижается :thumbs_up:'))


def step_52_no():
    print(emoji.emojize('Так тоже неплохо ️:OK_hand:️'))


def step_53_yes():
    print(emoji.emojize('Здорово! Котик больше не расстроен :thumbs_up:'))


def step_53_no():
    print(emoji.emojize('Вы обидели котика :crying_cat_face:'))


if __name__ == '__main__':
    step_1()
